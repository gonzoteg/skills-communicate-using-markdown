# Rutina diaria
## Planeo diario
## Revisión

###Lista de tareas:
- Primera
- Segunda
- Tercera
  
###Prueba de lista
- [ ] Sin cerrar
- [X] Cerrada
      
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
