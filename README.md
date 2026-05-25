# M-p Construção

Aplicativo Android para gerenciamento de construção.

## 📱 Sobre

Este é um aplicativo mobile desenvolvido em Kotlin para Android, focado em facilitar o gerenciamento de projetos de construção.

## 🛠 Requisitos

- Android Studio Flamingo ou superior
- JDK 11+
- Android SDK 24+
- Gradle 8.0+

## 📦 Instalação

### Método 1: Via Release (APK)
1. Acesse a aba [Releases](../../releases)
2. Baixe o arquivo `.apk` mais recente
3. Instale no seu dispositivo Android

**[📖 Guia Detalhado de Instalação](INSTALL.md)**

### Método 2: Build Local
```bash
git clone https://github.com/michelbp2404-ops/M-p-constru-o-.git
cd M-p-constru-o-
./gradlew build
./gradlew installDebug
```

## 🚀 Build & Release

### Gerar APK Debug
```bash
./gradlew assembleDebug
```

### Gerar APK Release
```bash
./gradlew assembleRelease
```

### Gerar Bundle (para Play Store)
```bash
./gradlew bundleRelease
```

### Criar Release (com GitHub Actions)
```bash
git tag v1.0.0
git push origin v1.0.0
```
O APK será gerado e publicado automaticamente no [Releases](../../releases)!

## 📁 Estrutura do Projeto

```
M-p-constru-o-/
├── app/                          # Módulo principal do app
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Código Kotlin/Java
│   │   │   ├── res/             # Recursos (layouts, strings, etc)
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                # Testes unitários
│   │   └── androidTest/         # Testes instrumentados
│   └── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

## 🤖 CI/CD

Este repositório usa **GitHub Actions** para automação:

✅ **Build Automático**: Em cada push para main/develop
✅ **Testes Automatizados**: Validação de código
✅ **Geração de APK/AAB**: Compilação automática
✅ **Release Automática**: Ao fazer push de tags (v*)

Veja `.github/workflows/` para mais detalhes.

## 📚 Documentação

- **[INSTALL.md](INSTALL.md)** - Guia completo de instalação
- **[DEVELOPMENT.md](DEVELOPMENT.md)** - Guia para desenvolvedores

## 🔐 Licença

Este projeto está licenciado sob a MIT License.

## 👨‍💻 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📧 Contato

Para dúvidas ou sugestões, abra uma [issue](../../issues).

---

**⭐ Gostou? Deixe uma estrela!**