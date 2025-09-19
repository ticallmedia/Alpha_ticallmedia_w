# Alpha_ticallmedia_w

#Version 4:

#Descripción: Primer Bot de Whatsapp para la empresa TicAll Media, integrado con IA de OpenAI

#Caracteristicas: 

#- AI gpt-3.5-turbo inicialmente, en python con openai==0.28.1
#- En gitgnore, se agrega el archivo .env
#- Las credenciales se suben en render directamente
#- Se actualiza presentación del portafolio como Lista, y prompt invoca lista no la genera
#- Se actualiza estado del usuario, para su categorización como posible cliente

#Actualiza 15/07/2025:
#-Se cambia bd SQLite a PostgreSQl para mejorar la persistencia de los datos
#-Tambien para utilizar mas de Una API para consultar la misma fuente de datos

#Actualiza 05/08/2025:
#-Se agrega la libreria 'langdetect', con el fin de poder identificar el idioma del usuario
#-Se crean las funciones: actualizar_idioma_si_cambia, guardar_idioma_usuario, obtener_idioma_usuario, detectar_idioma  
#para guardar, actualiza y obtener el idioma
#-se crea la tabal 'UsuarioLang' para capturar el idioma
#-se actualizan funciones para que siempre soliciten idioma
