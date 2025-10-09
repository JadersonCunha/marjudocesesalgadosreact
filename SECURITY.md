# Configuração de Segurança

## Variáveis de Ambiente

1. Copie o arquivo `.env.example` para `.env`:
```bash
cp .env.example .env
```

2. Configure suas credenciais reais no arquivo `.env`:
- `REACT_APP_EMAILJS_SERVICE_ID`: Seu Service ID do EmailJS
- `REACT_APP_EMAILJS_TEMPLATE_ID`: Seu Template ID do EmailJS  
- `REACT_APP_EMAILJS_PUBLIC_KEY`: Sua Public Key do EmailJS
- `REACT_APP_WHATSAPP_NUMBER`: Número do WhatsApp (formato: 5511999999999)
- `REACT_APP_EMAIL_TO`: Email de destino para receber os pedidos

## Instalação Atualizada

Execute os seguintes comandos para atualizar as dependências:

```bash
npm install
```

## Segurança

- Nunca commite o arquivo `.env` no Git
- Use apenas HTTPS em produção
- Mantenha as dependências sempre atualizadas