# Crypto Monitor – Aplicativo Android 📱💹

O **Crypto Monitor** é um aplicativo desenvolvido para a plataforma Android, com o objetivo de fornecer aos usuários um painel prático para consulta de preços atualizados de criptomoedas. O projeto foi feito com foco em organização de código, usabilidade e uso das principais tecnologias modernas do ecossistema Android.

---

## 🔍 O que o app oferece

- Listagem atualizada de criptomoedas com seus respectivos preços.
- Interface desenvolvida com Jetpack Compose.
- Atualizações dinâmicas através de requisições HTTP via Retrofit.
- Arquitetura organizada no padrão MVVM com uso de ViewModel e LiveData/Flow.
- Responsividade e carregamento assíncrono com coroutines.

---

## 🧾 Prints da Aplicação

**Insira aqui suas capturas de tela:**

- ![alt text](image.png) – Tela inicial com o valor zerado.
- ![alt text](image-1.png) – .Tela após clique de botão


---

## 📚 Stack e Ferramentas

- **Linguagem:** Kotlin
- **UI:** Jetpack Compose
- **Arquitetura:** MVVM
- **Async:** Kotlin Coroutines + Flow
- **API HTTP:** Retrofit
- **Injeção de dependências:** Hilt
- **Build:** Gradle com DSL em Kotlin

---

## 🧱 Estrutura de Pastas

```bash
android-crypto-monitor/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── carreiras/com/github/cryptomonitor/
│   │   │   │       └── MainActivity.kt
│   │   │   └── res/
│   ├── build.gradle.kts
├── build.gradle.kts
├── gradlew, settings.gradle.kts
└── gradle.properties
```

---

## 🧪 Testes Automatizados

O projeto já conta com estrutura para testes:

- **Testes instrumentados:** `app/src/androidTest/`
- **Testes unitários:** `app/src/test/`

---

## ▶️ Como executar o projeto

1. Clone este repositório:
```bash
git clone https://github.com/felipetome2862/android-crypto-monitor.git
```

2. Abra no **Android Studio** e aguarde a sincronização das dependências.

3. Certifique-se de que a API que está sendo consumida esteja funcionando.

4. Rode o projeto em um emulador ou dispositivo real com conexão de rede.

---

## 🌐 Permissões necessárias

No `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.INTERNET" />
```

---

## 📦 Exemplo de Dependências (Gradle App)

```kotlin
dependencies {
    implementation("androidx.core:core-ktx:1.9.0")
    implementation("androidx.compose.material:material:1.3.0")
    implementation("com.squareup.retrofit2:retrofit:2.9.0")
    implementation("com.google.dagger:hilt-android:2.44")
    kapt("com.google.dagger:hilt-compiler:2.44")
}
```

---


