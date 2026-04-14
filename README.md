<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://i.imgur.com/TTcg1Go.png" />
</div>

## ☁️ Integração Firebase

* **Google Authentication:** Sistema de login seguro que permite aos usuários salvar suas criações em uma conta pessoal.
* **Firestore Collection:** Uma base de dados em tempo real para armazenar o histórico de QR Codes, configurações personalizadas e estatísticas de uso.

## 🚀 Diferenciais Competitivos

* **AI Content Optimization:** Integrado com a API do **Gemini**, a ferramenta analisa o conteúdo (como URLs longas ou textos complexos) e sugere versões otimizadas para garantir que o QR Code seja mais fácil de ler e esteticamente limpo.
* **AI Auto-Naming:** Ao salvar um QR Code, a IA gera automaticamente um nome descritivo curto baseado no conteúdo, facilitando a organização da sua coleção.
* **Premium Export (High-Res):** Um toggle de "Alta Resolução" que dobra a densidade de pixels do QR Code para exportações destinadas à impressão profissional.
* **History & Analytics:** Uma aba de histórico dedicada onde você pode gerenciar seus códigos salvos, ver o número de "scans" (simulados via banco de dados) e restaurar configurações antigas com um clique.

## 🛠️ Tecnologias Utilizadas

* **Frontend:** React, Tailwind CSS, shadcn/ui.
* **Backend:** Firebase Auth, Firestore, Firebase Hosting.
* **Inteligência Artificial:** Google Gemini SDK.
* **Animações:** Motion (framer-motion).

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/6e81a7b0-3536-40aa-9f98-35a30e417ebf

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
