# mymovieAppSTB
Another small Movie App with an improved UI and new functionalities.


# MyMoviesApp

## Description ##

 La app deberá consultar a la API de "The Open Movie Database" : http://www.omdbapi.com/
 
A nivel funcional se espera un campo de texto donde el usuario deberá ingresar el nombre de la película o serie que desea buscar. La aplicación debe reaccionar acorde y mostrar resultados cada vez que se encuentre una coincidencia. Además se deberá presentar un filtro por tipo, ya sea película o serie. La UI deberá tener la siguiente estructura:

<img src="/demoImages/requirements_1.png" width="40%">

 Cuando el usuario presione el poster o el título deberá navegar a una página de detalles que muestre el nombre, tipo, poster, descripción y puntajes de IMDB. La UI se deberá presentar de la siguiente manera:


<img src="/demoImages/requirements_2.png" width="40%">


### App Demo ###

See the app live in the following video. Login, Top Movies and Search Option.

<img src="/demoImages/demoVideo_compressed.gif" width="40%">


## ¡Antes de comenzar! ##

- Open the config.dart file in lib folder
- Add your TMDB api key

```
String getApiKey() {
  return 'YOUR_TMDB_API_KEY';
}
```


## How to run the application? ##

```
flutter run
```

## Previews ##

### Home ###

<img src="/demoImages/requirements_1.png" width="40%">

### Movie Details ###

<img src="/demoImages/requirements_1.png" width="40%">

## License ###

...
