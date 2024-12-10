# Observação Importante:

Este projeto utiliza a API da OpenAI para processar mensagens no chat. 

Atualmente, o projeto está vinculado à minha conta pessoal, que está sujeita a:
- Limitações de uso gratuito.
- Cota que pode se esgotar, impedindo o funcionamento do projeto.

# Caso o projeto não funcione ao testar:

## Isso não é um bug, mas sim uma limitação de uso da API devido à cota esgotada.
## Se preferir, você pode fazer o teste do projeto usando sua chave: Basta gerar uma key no site do OpenAI, ir no arquivo openai.ts e substituir:

const openai = new OpenAI({
  apiKey: process.env.OPENAI_API_KEY, 
  dangerouslyAllowBrowser: true,
});

const openai = new OpenAI({
  apiKey: 'SUA CHAVE AQUI', 
  dangerouslyAllowBrowser: true,
});

### ATENÇÃO: Esta alteração é apenas para testes locais. Não exponha a sua chave em repositórios públicos ou em projetos que possam ser compartilhados.

### Agradeço pela compreensão!
