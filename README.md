# Sheila Oliveira Advocacia – Landing Page

Esta pasta contém os arquivos de uma landing page simples para o
escritório de advocacia de Sheila Oliveira. O objetivo é oferecer uma
presença online clara e profissional que permita aos clientes
encontrá‑la facilmente e entrar em contato.

## Arquivos incluídos

- **index.html**: a página principal com seções para apresentação,
  áreas de atuação, chamada para contato e formulário de contato.
- **style.css**: estilos personalizados baseados na paleta de cores
  fornecida (vermelho, dourado e tons neutros).
- **README.md**: este guia rápido com instruções para publicação.

## Como visualizar localmente

Se você quiser verificar como a página aparece antes de publicá‑la,
basta abrir o arquivo `index.html` no seu navegador. Você pode fazer
isso clicando duas vezes no arquivo ou arrastando‑o para a janela do
navegador.

## Personalização

- **Formulário**: o formulário de contato utiliza o serviço gratuito
  [Formspree](https://formspree.io/) para enviar mensagens por e‑mail
  sem necessidade de back‑end. Para que as mensagens sejam entregues
  corretamente, crie uma conta no Formspree, configure um formulário e
  substitua `your-form-id` no atributo `action` do `<form>` pelo ID
  gerado.
- **Informações de contato**: atualize o endereço de e‑mail no link
  `mailto:` e adicione outros detalhes (telefone, redes sociais) na
  seção "Contato" ou no rodapé, conforme necessário.
- **Conteúdo**: adapte textos, títulos e imagens conforme as
  especialidades e o tom desejado.

## Como publicar

Há várias maneiras de tornar esta página acessível na internet. Aqui
estão duas opções populares e gratuitas:

### 1. GitHub Pages (recomendado para iniciantes)

1. Crie uma conta no [GitHub](https://github.com/) se ainda não
   tiver uma.
2. No GitHub, clique em **New repository** (novo repositório). Dê um
   nome (por exemplo, `sheila-oliveira-site`) e deixe o repositório
   público.
3. Faça o upload dos arquivos desta pasta (`index.html`, `style.css` e
   `README.md`) para o repositório. Você pode arrastá‑los na interface
   web ou usar o Git no seu computador.
4. Nas configurações do repositório (**Settings** → **Pages**), em
   "Source" escolha a branch principal (geralmente `main`) e a pasta
   raiz (`/root`). Salve.
5. O GitHub gerará um link com o formato
   `https://seuusuario.github.io/nome-do-repositorio`. Após alguns
   minutos, seu site estará no ar nesse endereço.

### 2. Netlify

1. Acesse [Netlify](https://www.netlify.com/) e crie uma conta.
2. Clique em **Add new site** → **Import an existing project** e
   conecte‑se ao GitHub (ou faça upload manual dos arquivos se
   preferir).
3. Selecione o repositório onde o site está (ou arraste a pasta com os
   arquivos) e configure as opções de build. Para este site estático
   simples, não é necessário comando de build nem pasta de saída
   especial; deixe em branco.
4. Após publicar, o Netlify fornecerá um endereço personalizado
   (ex.: `https://seu-site.netlify.app`). Você pode configurar um
   domínio próprio mais tarde.

## Usando um domínio próprio

Caso deseje um domínio próprio (por exemplo,
`sheilaoliveira.adv.br`), registre o domínio em um provedor (como
Registro.br) e aponte o DNS para o serviço de hospedagem que você
escolher (GitHub Pages ou Netlify oferecem instruções claras para
isso).

## Suporte

Se você encontrar dificuldades durante a configuração ou publicação,
sinta‑se à vontade para procurar tutoriais adicionais no YouTube ou
na própria documentação do serviço escolhido. As comunidades do
GitHub e Netlify também oferecem fóruns de suporte úteis.