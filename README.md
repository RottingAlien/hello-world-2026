# Hello World

Página simples que mostra **"Hello World"** e a previsão do tempo para os próximos 7 dias em **Castelo Branco, Portugal** (39,82° N, 7,49° O).

- A previsão é obtida no browser a partir da API gratuita [Open-Meteo](https://open-meteo.com/) (sem chave de API), com fuso horário Europe/Lisbon.
- Para cada dia: dia da semana e data, ícone e descrição do tempo (códigos WMO), temperatura máxima/mínima, probabilidade e quantidade de precipitação, vento máximo e direção dominante.
- Se a API falhar, a página mostra uma mensagem de erro com um botão para tentar novamente.

## Ver localmente

Basta abrir `index.html` no browser, ou servir a pasta:

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## GitHub Pages

O workflow `.github/workflows/pages.yml` publica a página no GitHub Pages a cada push para `main`. Em **Settings → Pages**, a fonte deve estar definida como **GitHub Actions**.

Dados meteorológicos: Open-Meteo.com (CC BY 4.0).
