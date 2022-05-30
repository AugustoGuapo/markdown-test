<!-- Encabezados -->
# Mi título
## Mi título h2
### Titulo h3
#### titulo h4
##### titulo h5
###### titulo h6

<!-- formatos de texto de párrafo -->

*Cursiva*

**Negrita**

~~Tachado~~

<!-- Listas desoredanadas -->
* Manzana
  * Manzana 2
* Peras
  * Peras 2
* Otra cosa
  * Otra cosa 2
    * Otra cosa 3

<!-- Listas ordenadas -->
1. Pasar calculo
2. Conquistar al mundo
3. Comprar un pan

<!--Hipervínculos-->

[Visita mi Github](https://www.github.com/AugustoGuapo)
<!--Hipervínculo con título personalizado -->

[Visita mi Github](https://www.github.com/AugustoGuapo "Anda pues")

<!--Cita y lineas divisorias-->
> Esto es una cita
---
___

<!--Cita de código-->
`print("Hello World")`

```python
for groups in phoneRegex.findall(texto):
    phoneNum = '-'.join([groups[1],groups[4],groups[6]])
    if groups[8] != '':
        phoneNum += ' x' + groups[8]
    coincidencias.append(phoneNum)
```

```java
System.out.println("Hello world!");
```

<!--Llamado de imágenes-->
![Logo del mejor equipo](https://www.realmadrid.com/StaticFiles/RealMadridResponsive/images/static/og-image.png "Son 14 papá!!")

<!--Markdown de github-->
* [x] Tarea completada
* [ ] Tarea sin completar