<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4776E6,100:1E3C72&height=210&section=header&text=ICT&fontSize=48&fontAlignY=38&fontColor=ffffff&desc=Alba-rosa.cz&descAlignY=60&descSize=16&animation=fadeIn" alt="ICT" width="100%"/>
</p>

# Alba-rosa.cz · ICT

> Prohlížeč souborů a složek s výukovými ICT materiály.

🌐 **Živý web:** <https://alba-rosa.cz/ICT/>  
📂 **Kolekce:** Alba-rosa.cz  
👤 **Autor:** [@jurapascal](https://github.com/jurapascal)

---

## O projektu

Webový prohlížeč souborů a složek (výukové materiály k ICT) běžící jako podsložka
domény `alba-rosa.cz`.

## Technologie

- **PHP** (listování a servírování souborů)

## Nasazení

Nasazuje se **automaticky přes GitHub Actions** (workflow `Deploy`) po každém pushi do `main`. Nahrávají se jen změněné soubory přes vlastní FTP účet `w237642_ghict`, který vidí jen složku `/ICT/`; výsledek přijde na Discord. Co se nenahrává a co je jen na serveru, je v `.github/deploy.json`.

FTP na Wedos, podsložka `/ICT/` domény alba-rosa.cz.
