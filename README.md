# TecJustiça Transcribe

Transcrição automática de audiências judiciais com WhisperX. Suporte a GPU NVIDIA para performance, funciona offline.

## Instalação

### Windows (PowerShell)

```powershell
irm https://raw.githubusercontent.com/marcosmarf27/tecjustica-transcribe-desktop-releases/main/install.ps1 | iex
```

### Linux

```bash
curl -fsSL https://raw.githubusercontent.com/marcosmarf27/tecjustica-transcribe-desktop-releases/main/install.sh | bash
```

### Download manual

Baixe a versão mais recente na [página de releases](https://github.com/marcosmarf27/tecjustica-transcribe-desktop-releases/releases/latest).

- **Windows**: baixe o `.exe` e execute
- **Linux**: baixe o `.AppImage`, torne executável (`chmod +x`) e execute

## Primeiro uso

No primeiro uso, o app faz setup automático:
- Instala Python (se necessário)
- Instala ffmpeg (se necessário)
- Cria ambiente virtual com PyTorch + WhisperX (~3 GB de download)

### Pré-requisitos

- **GPU NVIDIA** (recomendado): driver 560+ para aceleração CUDA
- **Internet**: necessário no primeiro uso para o setup automático
