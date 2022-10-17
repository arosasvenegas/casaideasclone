# CasaIdeas Chile  

Repertorio base que contiene el clone de la tienda CasaIdeas Chile.

~ agregar imagen aqui de la tienda ~

## configuración 

### Paso 1 -  Configuración Básica 

Acceder a la [Guía básica de configuración](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1)de VTEX IO y seguir todos los pasos. 

Al final de la configuración, debe tener instalada la interfaz de línea de comandos VTEX (Toolbelt).

### Paso 2 - Clonación del repositorio

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) este repositorio a sus archivos locales para poder empezar a trabajar efectivamente en él.

Luego, acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editar el manifest.json

Una vez en el directorio del repositorio, es hora de editar el `manifest.json` del Minimum Boilerplate. 

Una vez en el archivo, debes remplazar los valores de `vendor` y `account`. `vendor` es el nombre de la cuenta que estas trabajando, nuestro partner y `account` es el nombre que elijas para tu tienda. Por ejemplo:

```json
{
  "vendor": "partner",
  "name": "my-test-store",
}
```

### Paso 4 -  Instalar apps necesarias

Con el fin de utilizar Store Framework y trabajar en el tema de su tienda, es necesario tener instalados `vtex.store-sitemap` y `vtex.store` .

Ejecutar  `vtex list`, para comprobar si esas aplicaciones ya están instaladas. 

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 -  Desinstalar el store'themepredeterminado

Ejecutando `vtex list`, puede verificar si cualquier tema está instalado.

Es común tener ya un `vtex.store-theme` instalado cuando se inicia el proceso de desarrollo de la tienda. 

Por lo tando, si lo encuentras en la lista de la aplicación, copie el nombre y usar junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme
```

### Paso 6- Ejecute un preview de la tienda

Siempre asegurarse de donde estammos trabajando, ya que, debemos evitar trabajar en master. para esto, utilice el comando `vtex whoami`
Entonces ha llegado el momento de subir todos los cambios que hizo en sus archivos locales a la plataforma. Para eso, use el comando `vtex link`. 


Si el proceso se ejecuta sin errores, el siguiente mensaje aparecerá: `App linked successfully`. Entonces, ejecute el comando `vtex browse` para abrir una ventana del navegador que tiene su tienda vinculada en ella.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

### Store Component Apps
1. "vtex.store": "2.x"
2. "vtex.store-header": "2.x"
3. "vtex.store-newsletter": "1.x"
4. "vtex.store-icons": "0.x"
5. "vtex.modal-layout": "0.x"
6. "vtex.product-summary": "2.x"
7. "vtex.product-list": "0.x"
8. "vtex.store-footer": "2.x"
9. "vtex.store-components": "3.x"
10. "vtex.styleguide": "9.x"
11. "vtex.slider": "0.x"
12. "vtex.carousel": "2.x"
13. "vtex.shelf": "1.x"
14. "vtex.menu": "2.x"
15."vtex.minicart": "2.x"
16. "vtex.product-details": "1.x"
17. "vtex.product-kit": "1.x"
18. "vtex.search-result": "3.x"
19. "vtex.login": "2.x",
20. "vtex.my-account": "1.x"
21. "vtex.flex-layout": "0.x"
22. "vtex.rich-text": "0.x"
23. "vtex.store-drawer": "0.x"
24. "vtex.locale-switcher": "0.x"
25. "vtex.product-quantity": "1.x"
26. "vtex.product-identifier": "0.x"
27. "vtex.product-specification-badges": "0.x"
28. "vtex.product-review-interfaces": "1.x"
29. "vtex.telemarketing": "2.x"
30. "vtex.order-placed": "2.x"
31. "vtex.stack-layout": "0.x"
32. "vtex.tab-layout": "0.x"
33. "vtex.responsive-layout": "0.x"
34. "vtex.slider-layout": "0.x"
35. "vtex.iframe": "0.x"
36. "vtex.breadcrumb": "1.x",
37. "vtex.sticky-layout": "0.x"
38. "vtex.add-to-cart-button": "0.x"
39. "vtex.search": "1.x",
40. "vtex.checkout-summary": "0.x"
41. "vtex.disclosure-layout": "1.x"
42. "vtex.product-price": "1.x"
43. "vtex.store-link": "0.x"

### Custom Apps 

1. "itgloberspartnercl.whatsapp-button": "0.x",
2. "itgloberspartnercl.add-to-cart-info": "0.x",
3. "itgloberspartnercl.bullets-diagramation": "0.x",
4. "itgloberspartnercl.custom-department-search": "0.x",
5. "itgloberspartnercl.pdf-reader": "0.x",
6. "itgloberspartnercl.quick-order": "0.x",
7. "itgloberspartnercl.special-diagramation": "0.x"

### Contributors
Angela Rosas Venegas
