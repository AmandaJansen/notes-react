# Aplicativo de Notas

Este é um componente React para criar notas de forma interativa, permitindo a criação de notas de texto ou por meio de gravação de áudio convertido automaticamente em texto.

## Funcionalidades Principais
* Criação de notas de texto.
* Gravação de notas em áudio, convertidas automaticamente em texto.

## Dependências
* @radix-ui/react-dialog: Utilizado para criar o diálogo de criação de nota.
* lucide-react: Fornece o ícone de fechamento para fechar o diálogo.
* react: Biblioteca de construção de interfaces do usuário.
* sonner: Biblioteca utilizada para exibir notificações de toast.

## Comportamento
* Ao clicar no botão "Adicionar nota", um diálogo será exibido.
* O usuário pode começar a gravar uma nota em áudio clicando no botão "gravando uma nota" ou escrever texto diretamente no campo de texto.
* Ao terminar de gravar ou digitar, o usuário pode salvar a nota clicando no botão "Salvar nota".
* Notificações de toast serão exibidas para informar o usuário sobre o status da operação (sucesso ou erro).

## Suporte
Este componente utiliza a API de Reconhecimento de Fala, portanto, é necessário que o navegador do usuário ofereça suporte a essa API.
