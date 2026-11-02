# Agente de IA - Observatorio de Ocotlan (Entrega I1)
Mi agente usa Gemini para tomar las decisiones, consulta informacion y pide la cofirmacion humana

# Decision seleccionada
Desicion "A": ("ventilar el salón", {"eco2_ppm", "tvoc_ppb", "aqi", "temp_c", "rh_pct"}),

# Reglas de seguridad
1. Verificar variables de cada opcion
2. Necesita aprovacion humana
3. Palabras engañosas (mia) - bloqueo intentos de consulta si en la misma hay palabras sospechosas

# Instrucciones de ejecucion
DEBES ESTAR EN ESTA RUTA: C:\Users\godin\Desktop\SeptimoSemestre\InteligenciaArtificial\agente-Godinez>

# Poner en la terminal:
$env:GEMINI_API_KEY="ClaveDeGemini"
$env:CAMINO="gemini"

python generar\_datos.py
python agente.py "¿Debo abrir las ventanas?"
