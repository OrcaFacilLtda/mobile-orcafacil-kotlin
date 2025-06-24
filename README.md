# 📱 OrçaFácil - Módulo Mobile (Android/Kotlin)

Este repositório contém o aplicativo mobile do projeto **OrçaFácil**, desenvolvido em **Kotlin** para dispositivos Android. O app oferece aos usuários e prestadores de serviços uma forma prática e ágil de acessar todas as funcionalidades da plataforma diretamente no smartphone.

> ⚠️ Este projeto representa **somente o aplicativo mobile** do sistema OrçaFácil.

---

## 🧭 Funcionalidades

- Login e cadastro de usuários e prestadores
- Criação de solicitações de orçamento com descrição e categoria
- Recebimento e comparação de propostas recebidas
- Avaliação de serviços prestados
- Notificações sobre novas mensagens, propostas ou atualizações
- Acompanhamento do histórico de solicitações
- Interface amigável e adaptada para dispositivos móveis Android

---

## 📂 Estrutura do Projeto

- `app/` – Código-fonte principal do app Android
  - `src/`
    - `main/`
      - `java/` – Classes Kotlin do aplicativo
      - `res/` – Recursos visuais (layouts, strings, cores, etc.)
      - `AndroidManifest.xml` – Configurações principais
  - `build.gradle` – Configuração do módulo
- `build.gradle (Project)` – Configuração do projeto
- `README.md`

---

## ⚙️ Como Executar

### Pré-requisitos

- Android Studio Flamingo ou superior
- SDK Android 33 ou superior
- Dispositivo físico Android ou emulador

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/databrick/orcafacil-mobile.git
   ```

2. Abra o projeto no **Android Studio**.

3. Aguarde o Gradle sincronizar e resolva eventuais dependências.

4. Conecte um dispositivo Android ou inicie um emulador.

5. Execute o app (`Run > Run 'app'`).

> 💡 O app se comunica com a API do back-end (`orcafacil-backend`) — certifique-se de configurar a URL base da API corretamente no projeto (por exemplo, via `BuildConfig` ou `env.properties`).

---

## 🔗 Integração

Este aplicativo integra-se com os seguintes módulos da plataforma **OrçaFácil**:

- [`orcafacil-backend`](https://github.com/databrick/orcafacil-backend): serviços de API e banco de dados
- [`orcafacil-frontend`](https://github.com/databrick/orcafacil-frontend): interface web para usuários e administradores

---

## 📄 Licença

Distribuído sob a **Licença de Uso Estudantil**. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.

---

> Desenvolvido por **OrcaFacilLtda** – Parte integrante do ecossistema OrçaFácil  
> © 2025 Todos os direitos reservados
```

