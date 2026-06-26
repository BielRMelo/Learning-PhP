# CLAUDE.md

## Skills instaladas

### /watch — Analisar vídeos
Skill que permite ao Claude analisar vídeos (URLs ou arquivos locais).

**Instalação:** `~/.claude/skills/watch` (fonte: https://github.com/bradautomates/claude-video)

**Como usar:**
```
/watch https://youtu.be/URL "o que acontece aos 30 segundos?"
/watch ~/video.mp4 --start 2:15 --end 2:45 "resuma essa seção"
```

**Dependências necessárias:**
- `ffmpeg` — extração de frames
- `yt-dlp` — download de vídeos
- Opcional: chave de API Groq ou OpenAI para transcrição por Whisper
