# Automation News — Landing / Ofertë

Faqe e vetme statike (HTML) që përdoret si **landing page ofertë** për t'ua prezantuar
botin *Automation News* portaleve të lajmeve.

## Përmbajtja
- `index.html` — e gjithë faqja (HTML + CSS inline, pa varësi, pa build).

## Deploy në Vercel
1. Shko te [vercel.com](https://vercel.com) → **Add New… → Project**
2. **Import** repo-n `automation-news-` nga GitHub
3. Framework Preset: **Other** (site statik) — pa komandë build, pa output dir
4. **Deploy** → gati brenda sekondash

Vercel e ripublikon automatikisht sa herë bën `git push`.

## Përshtatje para dërgimit
Në `index.html`, ndrysho:
- Çmimin ("nga €199/muaj")
- Kontaktin poshtë: `[Emri juaj] · [+383…] · [email]`
- Lidhjet e butonave "Kërko demo" (mailto: ose WhatsApp)
