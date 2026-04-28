# Flux - Releases

Repositório público de distribuição das versões APK do aplicativo Flux.

Este repositório é usado pelo aplicativo para verificar a versão mais recente disponível e controlar atualizações obrigatórias.

## Versão atual

Versão mais recente: `1.0.0`

## Instalação

Baixe o APK mais recente na aba **Releases** deste repositório.

Pode ser necessário permitir a instalação de aplicativos de fontes desconhecidas no Android.

## Controle de atualização

O aplicativo consulta o arquivo `version.json` deste repositório para verificar:

- versão mais recente disponível;
- versão mínima suportada;
- se a atualização é obrigatória;
- link de download do APK.

## Arquivo de versão

O arquivo usado pelo app é:

```txt
version.json
