<p align="center">
  <img src="assets/icon_256.png" width="128" alt="Ícone do MHCODE">
</p>

<h1 align="center">MHCODE</h1>

<p align="center">
  Leitor de QR code para Windows: lê QR codes de imagens, PDFs, documentos e prints de tela,
  e mostra o conteúdo para você conferir <b>antes</b> de abrir.
</p>

<p align="center">
  <a href="https://github.com/gab-silvaa/mhcode-app/releases/latest"><b>⬇ Baixar a versão mais recente</b></a>
</p>

---

## Por que usar

Abrir um QR code no celular para depois digitar o link no computador é lento e arriscado.
O MHCODE lê o QR direto do arquivo que já está no seu computador e mostra exatamente para
onde ele leva, avisando quando o link não é de um site confiável.

## Recursos

- **Arraste e solte** um ou vários arquivos na janela
- **Cole um print** da tela: `Win + Shift + S`, selecione o QR e aperte `Ctrl + V` no MHCODE
- Lê **imagens** (PNG, JPG, BMP...), **PDF**, **Word**, **Excel** e **PowerPoint**,
  inclusive QR colado como imagem vetorial (EMF/WMF)
- Em PDFs com várias páginas, informa **em qual página** está cada QR code
- Leitura de arquivos grandes pode ser **cancelada** a qualquer momento (botão Cancelar ou `Esc`)
- Reconhece **links, PIX copia e cola, Wi-Fi, e-mail, telefone** e texto comum
- **PIX**: mostra para quem é, o valor, a cidade e a chave antes de você pagar, e avisa
  com **"Código inválido · não pague"** quando o código foi alterado ou está danificado
- **Segurança**: links fora da lista de domínios confiáveis pedem confirmação antes de abrir,
  e links sem HTTPS são sinalizados
- Lista de **domínios confiáveis editável**
- Funciona **100% offline**: nenhum arquivo ou conteúdo é enviado para a internet

## Instalação

1. Vá em [**Releases**](https://github.com/gab-silvaa/mhcode-app/releases/latest) e baixe o arquivo
   `MHCODE_Setup_<versão>.exe`.
2. Dê dois cliques no instalador e siga os passos.
   - Não precisa de senha de administrador.
   - Cria atalhos na Área de Trabalho e no Menu Iniciar.
3. Pronto. Abra o **MHCODE** pelo atalho.

> **O Windows mostrou "O Windows protegeu o computador"?**
> Isso acontece com programas novos que ainda não têm assinatura digital paga.
> Clique em **Mais informações** e depois em **Executar assim mesmo**.

**Requisitos:** Windows 10 ou 11 (64 bits).

## Como usar

| Para ler um QR de...      | Faça assim                                                          |
|---------------------------|---------------------------------------------------------------------|
| Um arquivo                | Arraste o arquivo para a janela, ou clique para escolher            |
| Vários arquivos           | Arraste todos de uma vez                                            |
| Algo que está na tela     | `Win + Shift + S`, recorte o QR e aperte `Ctrl + V` no MHCODE      |
| Um arquivo copiado        | Copie no Explorer (`Ctrl + C`) e cole no MHCODE (`Ctrl + V`)        |

Cada QR encontrado aparece num cartão com o conteúdo, o tipo (link, PIX, Wi-Fi...) e botões
para **copiar** ou **abrir**.

### PIX

Ao ler um QR de PIX, o MHCODE mostra o que está escrito no código: **nome do recebedor,
cidade, valor** (ou "a definir por quem paga") e a **chave** (CPF aparece parcialmente
escondido). O botão **Copiar** copia o código para colar no banco em *Pix → Pix copia e cola*.

- **"Código inválido · não pague"**: o código foi alterado ou está danificado.
- **"Confira o nome no banco"**: o nome dentro do QR é escrito por quem gerou o código.
  Só pague se o app do banco mostrar o mesmo recebedor.
- **Cobrança dinâmica** (lojas, boletos): o valor final fica no banco; o MHCODE mostra
  qual site emitiu a cobrança.

### Domínios confiáveis

Links de domínios da lista abrem direto; os demais pedem confirmação. A lista vem com
`gov.br`, `jus.br`, `onr.org.br` e `registradores.org.br` e pode ser editada dentro do programa.
Ela fica salva em `%APPDATA%\MHCODE\config.json`.

## Atualizar

Baixe o instalador da versão nova e instale por cima. A versão anterior é substituída e suas
configurações são mantidas.

## Desinstalar

**Configurações → Aplicativos → Aplicativos instalados → MHCODE → Desinstalar**
(ou "Adicionar ou remover programas").

## Privacidade

O MHCODE não tem conexão com a internet, não coleta dados e não envia nada a lugar nenhum.
A leitura dos QR codes acontece inteiramente no seu computador. A internet só é usada quando
**você** escolhe abrir um link, e aí quem abre é o seu navegador.

## Sobre o nome

**MH** é uma homenagem a **Masahiro Hara**, o engenheiro japonês que criou o QR code em 1994.
As cores do programa vêm da bandeira do Japão (*hinomaru*).

## Problemas e sugestões

Encontrou um QR que o MHCODE não leu, ou tem uma ideia? Abra uma
[issue](https://github.com/gab-silvaa/mhcode-app/issues) contando o que aconteceu
(se puder, anexe o arquivo de exemplo, desde que não tenha dados pessoais).

---

© 2026 Gabriel Silva. Todos os direitos reservados. O instalador é distribuído gratuitamente;
o código-fonte não é público.
