<div align="center">

# STAR5

### Um desktop Debian com personalidade Y2K.

KDE Plasma · Debian 13 · PCs Intel e AMD de 64 bits

<a href="https://img.shields.io/badge/Debian-13-A80042?style=flat-square"><img alt="Debian 13" src="https://img.shields.io/badge/Debian-13-A80042?style=flat-square"></a>
<a href="https://img.shields.io/badge/KDE-Plasma-5B8F7A?style=flat-square"><img alt="KDE Plasma" src="https://img.shields.io/badge/KDE-Plasma-5B8F7A?style=flat-square"></a>
<a href="https://img.shields.io/badge/Arquitetura-amd64-77747B?style=flat-square"><img alt="amd64" src="https://img.shields.io/badge/Arquitetura-amd64-77747B?style=flat-square"></a>
<a href="https://github.com/maisumacontavic-bit/star5/releases/latest"><img alt="Versão mais recente" src="https://img.shields.io/github/v/release/maisumacontavic-bit/star5?include_prereleases&style=flat-square&color=D9A4B2"></a>

**[Baixar a ISO](https://drive.google.com/file/d/14OO_m8sGziel76AbQFwAXyJMjHINmbQL/view?usp=sharing)**

</div>

---

## Uma cara própria para o KDE

Rosa empoeirado, cinza-carvão e verde-musgo encontram o visual Y2K e os detalhes pixel art. O Star5 combina uma barra superior simples, dock centralizado, encaixe de janelas e uma alternativa de tema claro.

## A imagem

Baixe `Star-Five-amd64.hybrid.iso` pelo [Google Drive](https://drive.google.com/file/d/14OO_m8sGziel76AbQFwAXyJMjHINmbQL/view?usp=sharing). A ISO é o único arquivo distribuído publicamente pelo projeto; o código-fonte permanece privado.

| | |
|---|---|
| **Base** | Debian 13 Trixie |
| **Desktop** | KDE Plasma |
| **Arquitetura** | AMD64 / Intel 64-bit |
| **Formato** | ISO híbrida inicializável, live e instalável |

Grave a ISO em um pendrive ou abra-a em uma máquina virtual. No menu de boot, escolha **Live system** para experimentar ou inicie o instalador Debian para instalar no computador.

## O que vem no Star5

- **Star5 Control** para aparência, encaixe de janelas e informações do computador.
- **StarMind**, assistente local com `llama.cpp` e Gemma 3 1B.
- **Docker Engine** e KDE Discover com Flathub.
- Firefox, Dolphin, LibreOffice e coleção adicional de aplicativos Flatpak.

O modelo de IA, com aproximadamente 806 MB, é baixado ao abrir o StarMind pela primeira vez. Depois do download, as conversas são processadas no computador. A coleção de Flatpaks é baixada em segundo plano depois da instalação.

## Nota sobre esta versão

Star5 0.1.0 é uma versão de prévia. A ISO foi compilada e inspecionada como mídia inicializável; o comportamento ainda precisa ser conferido em diferentes computadores. Faça cópia dos seus arquivos antes de instalar qualquer sistema operacional.

## Licenças

Esta imagem reúne Debian, KDE Plasma, `llama.cpp`, Gemma e aplicativos independentes. Cada componente tem seus próprios termos. O Gemma não está dentro da ISO: ele é baixado pelo StarMind sob os [termos do Gemma](https://ai.google.dev/gemma/terms). O runtime do `llama.cpp` e sua licença acompanham a distribuição.
