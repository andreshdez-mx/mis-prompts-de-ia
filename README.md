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
entonces puedo confiar que fueron cientos de miles de requests de esa ip durante la mañana del dia de hoy?
------------------------------
a que te refieres con (pri. 19) en endurecer regla RateLimit o a (pri. 20)  en Reforzar Rate_Limit_JA4 ?
------------------------------
en Protección del sitemap y secciones: Aplicar a que te refieres con esto: rate-limit más estricto o token/challenge ?
------------------------------
cómo implementar Challenge (token) ?
```
## 🎨 Alerta Urgente | WebErrorCodes 404 | Tablas SQL

### Analizar los Requests bloqueados por la regla
* **IA:** deepseek
* **Objetivo:** Detectar y analizar tráfico malicioso.
* **Prompt:**
```text
puedes actuar como un analista de seguridad y analizar los requests que hizo a mi sitio esta ip, incluyo archivo csv adjunto, y darme las posibles afectaciones y sugerencias a seguir revisa  y analiza todos los requests los status y ver qué pudo hacer el atacante
------------------------------
puedes tabular los status de los requests mencionando las cantidades de cada estado?
------------------------------
estas seguro?  yo vi en total 161 requests de esa ip
------------------------------
seguro? con la cantidad exacta de cada estado
```

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

## 📝  Alerta Urgente | WebErrorCodes 404 | Tablas SQL

### Analizar los Requests 404 de cierta ip que llegan al origen
* **IA:** LibreChat
* **Objetivo:** Detectar si es tráfico válido o malicioso.
* **Prompt:**
```text
analiza los requests de la siguiente ip 37.64.211.227  sobre el sitio de avisos de ocasion, la tabla de logs es: www_avisosdeocasion_com en la DB sampledb, busca los que pertenezcan ya al dia 02 de Septiembre del 2026, encuentra si fueron maliciosos y si lograron su objetivo y sugiere acciones a realizar.
```

## 📝  ALARM: "Anomaly Detection Errores 4xx distribuciones de CAMBRIDGE" in US East (N. Virginia)

### Analizar los Requests de cierta ip sobre el sitio mencionado
* **IA:** LibreChat
* **Objetivo:** Detectar si es tráfico válido o malicioso.
* **Prompt:**
```text
puedes analizar el tráfico de esta ip 45.203.220.139 sobre el sitio cambridgemty.edu.mx los logs están en athena en la DB sampledb tabla www_cambridgemty_edu_mx los requests del día  2026-09-01 a partir de las 00 Hrs , revisar si es tráfico malicioso y sugerir posibles soluciones si es que lo es.
```



