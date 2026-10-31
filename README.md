# Reaksiya

Azərbaycan dilində virtual kimya laboratoriyası. Bu paket son yayımlanmış versiyadan (734fd734de8f8431ef0e6811e507a72b38b2aea2) götürülüb.

## İşə salmaq

Python 3 ilə bu qovluqda:

```bash
python3 -m http.server 8000
```

Brauzerdə http://localhost:8000 açın. Build və npm install tələb olunmur.

## Fayllar

- index.html — səhifə
- style.css — dizayn
- app.js — təcrübələr və oyun məntiqi

8 maddə, 5 seçilmiş təcrübə, 4 missiya. Hazır təcrübələr bir kliklə seçilir. Dəstəklənməyən seçimlər bloklanır. Kəşflər localStorage-da saxlanılır.

Animasiya sxematikdir; miqdar, qatılıq və temperatur hesablanmır. Elmi mənbələr saytdakı “Simulyasiya haqqında” bölməsindədir.

Google Fonts internetdən yüklənir; əlçatan olmadıqda sistem şriftləri işləyir. Backend və API açarı tələb olunmur.
