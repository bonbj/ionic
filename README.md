# Exemplo de uso das bibliotecas nativas do Ionic

Este projeto está sendo desenvolvido para demonstrar como utilizar as bibliotecas nativas do Ionic, com o objetivo de criar um guia de consulta para a comunidade. O projeto visa fornecer exemplos de implementação de cada uma das bibliotecas nativas do Capacitor, facilitando o aprendizado e a utilização dessas funcionalidades em aplicativos Ionic.

## Status atual

Atualmente, estou trabalhando na implementação da biblioteca:

- **@capacitor/action-sheet**

## Checklist de implementação das bibliotecas

- [ ] **@capacitor/action-sheet** (Em andamento)
- [ ] **@capacitor/app-launcher**
- [ ] **@capacitor/app**
- [ ] **@capacitor/browser**
- [ ] **@capacitor/camera**
- [ ] **@capacitor/clipboard**
- [ ] **@capacitor/device**
- [ ] **@capacitor/dialog**
- [ ] **@capacitor/filesystem**
- [ ] **@capacitor/geolocation**
- [ ] **@capacitor/google-maps**
- [ ] **@capacitor/haptics**
- [ ] **@capacitor/keyboard**
- [ ] **@capacitor/local-notifications**
- [ ] **@capacitor/motion**
- [ ] **@capacitor/network**
- [ ] **@capacitor/preferences**
- [ ] **@capacitor/push-notifications**
- [ ] **@capacitor/screen-reader**
- [ ] **@capacitor/share**
- [ ] **@capacitor/splash-screen**
- [ ] **@capacitor/status-bar**
- [ ] **@capacitor/text-zoom**
- [ ] **@capacitor/toast**

## Como rodar o projeto

1. versões do ambiente

   ```bash
   node -v
   v22.11.0

   java --version
   openjdk 21.0.5 2024-10-15 LTS
   OpenJDK Runtime Environment Temurin-21.0.5+11 (build 21.0.5+11-LTS)
   OpenJDK 64-Bit Server VM Temurin-21.0.5+11 (build 21.0.5+11-LTS, mixed mode, sharing)

   ionic -v
   7.2.0

2. Clone o repositório:

   ```bash
   git clone https://github.com/bonbj/ionic.git

   cd projeto-ionic

   npm install

   ionic cap add android
   ionic cap add ios

   ionic cap sync

   ionic cap run android
   ionic cap run ios