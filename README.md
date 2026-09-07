# 🤖 Mi Reporte de Prompts de IA

¡Bienvenido a mi colección de prompts! Aquí guardo y organizo las instrucciones que utilizo con diferentes Inteligencias Artificiales para optimizar mi flujo de trabajo.

## 🎨 ALARM: "Bloqueo en WAF de IPs que sobre pasan el RateLimit" in US East (N. Virginia)

### Analizar los Requests bloqueados por la regla
* **IA:** LibreChat
* **Objetivo:** Detectar si es tráfico válido bloqueado por algún ciclado o si es tráfico malicioso.
* **Prompt:**
```text
puedes analizar el tráfico de esta ip 170.203.120.3 sobre el sitio www.reforma.com del día  2026-09-05  partir de las 06 Hrs  los logs están en athena en la DB sampledb tabla www_reforma_com, revisar si es tráfico malicioso y sugerir posibles soluciones para las miles de peticiones de esta ip
------------------------------
entonces puedo confiar qye fueron cientos de mils de requests de esa ip durante la mañana del dia de hoy?
------------------------------
a que te refieres con (pri. 19) en endurecer regla RateLimit o a (pri. 20)  en Reforzar Rate_Limit_JA4 ?
------------------------------
en Protección del sitemap y secciones: Aplicar a que te refieres con esto: rate-limit más estricto o token/challenge ?
------------------------------
cómo implementar Challenge (token) ?
```
---

## 📝  ALARM: "Bloqueo en WAF de IPs que sobre pasan el RateLimitJA4" in US East (N. Virginia)

### Analizar los Requests bloqueados por la regla
* **IA:** LibreChat
* **Objetivo:** Detectar si es tráfico válido o malicioso.
* **Prompt:**
```text
estoy recibiendo alarmas de aws con esta alerta Bloqueo en WAF de IPs que sobre pasan el RateLimitJA4 con la WebACL-Prod, al revisar en athena veo miles de requests a esta url /libre/pos/poswidget.htm con referers de elnorte.com. reforma.com y mural.com.mx   puedes analizar esta información para ver si es tráfico válido y así permitir esta ruta como execpción para blqueo de  ja4fingerprint
------------------------------
logs del waf:  DB  logs_waf_s3_db tabla waf_logs_webacl-prod_ja4_day  los logs de la webACL_Prod están en la tabla waf_logs_webacl-prod_day  y el rango es de 2026-09-01, 01:30–02:15 UTC
```




