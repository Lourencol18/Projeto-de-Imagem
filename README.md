# Projeto de Imagem

Aplicação desktop desenvolvida em C# com Windows Forms e EmguCV (wrapper do OpenCV) para processamento, análise e reconhecimento de imagens.

## Descrição

Este projeto permite:

- abrir imagens locais;
- salvar a imagem processada;
- visualizar a imagem com zoom;
- desfazer alterações;
- converter imagens para escala de cinza;
- aplicar binarização;
- detectar e identificar regiões/objetos na imagem;
- visualizar histogramas e informações relacionadas à imagem.

A aplicação foi desenvolvida como um ambiente de estudo para processamento digital de imagens e operações de visão computacional.

## Tecnologias utilizadas

- C#
- .NET Framework 4.8
- WinForms
- EmguCV / OpenCV
- ZedGraph

## Estrutura do projeto

- `SS_OpenCV/` - projeto principal da aplicação
- `SS_OpenCV/MainForm.cs` - interface principal e ações de processamento
- `SS_OpenCV/ImageClass.cs` - funções de processamento de imagens
- `SS_OpenCV/Histograma.cs` - visualização de histogramas
- `SS_OpenCV/AuthorsForm.cs` - tela de autores
- `SS_OpenCV/InputBox.cs` - caixa de entrada

## Requisitos

- Windows 10 ou superior
- Visual Studio 2019 ou 2022
- .NET Framework 4.8
- Pacotes NuGet do projeto restaurados

## Como executar

1. Abra a solução `CG_OpenCV_2021.sln` no Visual Studio.
2. Verifique se o projeto `SS_OpenCV` está definido como projeto de inicialização.
3. Restabeleça os pacotes NuGet, se necessário.
4. Compile a solução.
5. Pressione `F5` para executar a aplicação.

## Como usar

1. Clique em `Arquivo > Abrir` para carregar uma imagem.
2. Escolha uma operação disponível no menu da aplicação.
3. Ajuste a visualização com zoom e controle da imagem.
4. Salve o resultado em `Arquivo > Salvar`.

## Observações

- O projeto é uma aplicação desktop antiga e foi construído com .NET Framework, então a execução é mais compatível com ambientes Windows.
- Algumas dependências podem exigir que o projeto seja compilado em ambiente com .NET Framework e bibliotecas do EmguCV corretamente instaladas.


