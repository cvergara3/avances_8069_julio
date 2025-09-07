# avances_8069_julio

El repositorio consta de tres códigos y un archivo base.

### Códigos:
1. shot_gathers_devito.ipynb: Requiere de entrada el modelo geológico de gempy llamado 'modelo_gempy_topografia_25m_res_3.pkl'. Este código genera el volumen sintético de velocidad de alta resolución y también los shot gathers 2D (7 lineas de fuentes con 512 receptores cada una)
2. unet_random.ipynb: Red de reconstrucción end to end con submuestreo aleatorio de trazas sísmicas.
3. unet_ste: Red de reconstrucción end to end con submuestreo basado en capas binarias entrenables aplicando STE.

### Archivo base:
'modelo_gempy_topografia_25m_res_3.pkl': Modelo geológico sintético exportado de gempy
