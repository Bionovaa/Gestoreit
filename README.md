# **Gestoreit: Monitoreo de Biodigestor**

Monitoreo de sensores por el protocolo LoRa para el monitoreo de iodigestor en el Estado de Hidalgo

## Descripción

El presente proyecto tiene como objetivo desarrollar un sistema de monitoreo remoto de sensores utilizando el protocolo LoRa para la gestión de biodigestores y el software de codigo abierto Zabbix en el estado de Hidalgo. El sistema permitirá recopilar datos en tiempo real de parámetros críticos como la temperatura, la presión, el monoxido de carbono y el dioxido de carbono, proporcionando información valiosa para optimizar el funcionamiento de biodigestores y mejorar la producción de biogás.

## Visuales

Capturas de pantalla, videos o GIFs que demuestran lo que hace el proyecto y cómo usarlo.

## Empezando 🚀

Por ahora no hay alguna forma de tener nuestro proyecto ya que se encuentra alojado en una maquina virtual, proximamente en un contenedor para el acceso para todos

### Prerrequisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

- Sistema Operativo: Linux nativo o de forma virtualizada
- Lenguaje de programación: C+
- Base de datos: Mariadb o MySQL
- Zabbix: Frontend, server y agente 2
- PHP

### Instalación 🔧

Puedes ver el siguiente enlace para instalar zabbix y configurarlo de forma exitosa en tu entorno

## Ejecutando las Pruebas ⚙️

Los siguintes comandos son fundamentales para garantizar que esta funcionando de forma datisfactorio

### 1.- Establecer conexion con la maquina virtual, gateway o server de zabbix
```bash
ping 192.0.0.0
```
### 2.- Ver el archivo log de zabbix agent2
Es fundamental para asegurarse de que se configuró de forma satisfactoria el agente zabbix con el gateway, es importante conocer donde esta ubicado
```bash
cat *ubicacion del log de zabbix*
```

### Pruebas de Principio a Fin 🔩

Para la interpretacion de datos debes acceder al dashboard de zabbix desde el navegador de la maquina o de forma remota conectandote en la misma red del dashboard poniendo la ip del ordenador acompañada de /zabbix, ejemplo:
```navegador
192.0.0.1/zabbix
```

### Pruebas de Estilo de Código ⌨️

Descripción y ejemplos de las pruebas de estilo que estás utilizando.

```bash
# proporciona un ejemplo
```

## Construido Con 🛠️

Explica qué tecnologías usaste para construir este proyecto. Aquí algunos ejemplos:

- [Ruby](https://www.ruby-lang.org/es/) - El lenguaje utilizado
- [Ruby on Rails](https://rubyonrails.org) - El framework web utilizado
- [Ruby gems](https://rubygems.org) - Gestión de dependencias
- [Postgresql](https://www.postgresql.org) - Sistema de base de datos
- [Bulma IO](https://bulma.io) - Framework de CSS

## Contribuyendo 🖇️

Las contribuciones son lo que hacen a la comunidad de código abierto un lugar increíble para aprender, inspirar y crear. Cualquier contribución que hagas es muy apreciada. Por favor, lee el [CONTRIBUTING.md](https://gist.github.com/brayandiazc/xxxxxx) para detalles sobre nuestro código de conducta, y el proceso para enviarnos pull requests.

## Soporte

Si tienes algún problema o sugerencia, por favor abre un problema o envianos un correo electronico _______________________.

## Roadmap

Posibles implementaciones al proyecto

- Implementar automatizacion al proyecto
- Agregar mas sensores para el monitoreo
- Optimizacion de codigo de la placa
- Implementacion de big data para el analisis de datos
- implementacion de computo en la nube

## Versionado 📌

Usamos [Git](https://git-scm.com) para el versionado. Para las versiones disponibles, ve las [etiquetas en este repositorio](https://github.com/your/project/tags).

## Autores ✒️

- **Alejandro Barrientos Escalante** - _Trabajo inicial_ - [Alejandro Barrientos](https://github.com/beofalejandro)
- **Ulises Porras Rosas** - _Trabajo inicial_ - [Ulises Porras](https://github.com/UlisesPR2101)
- **Elvis Jesus Martinez Lugo** - _Trabajo inicial_ - [Elvis Lugo](https://github.com/Elvis-Lugo)
- **Elizabeth Diaz Oropeza** - _Trabajo inicial_ - [Elizabeth Diaz](https://github.com/Elizabeth-Diaz-Oropeza)

Mira también la lista de [contribuidores]() que han participado en este proyecto.

## Expresiones de Gratitud 🎁

Estamos agradecidos por las contribuciones de la comunidad a este proyecto. Si encontraste cualquier valor en este proyecto o quieres contribuir, aquí está lo que puedes hacer:

- Comparte este proyecto con otros
- Muestra tu agradecimiento diciendo gracias en un nuevo problema.
- sigue al tarabjo de nuestros autores

---

Documentacion hecha con ❤️ por **ESCALIA**
