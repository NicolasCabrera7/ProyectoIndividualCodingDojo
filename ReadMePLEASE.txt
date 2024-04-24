Debido a problemas que tuve encontrando una api adecuada el programa funciona
usando un archivo json que se encuentra en el proyecto para poder tener info 
de los equipos, pero la informacion de los partidos si esta almacenada usando
mongoDB por lo que utilizando postman cargue la informacion de los partidos
y dicha informacion es la utilizada para que la pagina funcione correctamente,
a continuacion dejo un get que le hice a mi base de datos al momento de enviar 
el correo, se recomienda usar postman con el servidor corriendo y agregar los
partidos uno a uno usando POST en la siguiente direccion


URL de la base de datos:   http://localhost:5000/api/auth/match

Informacion de los partidos:

[
    {
        "_id": "662559abcefaea3b1735c368",
        "juego": "EDG-IG",
        "equipo1": "EDG",
        "equipo2": "IG",
        "imagen1": "https://cdn.pandascore.co/images/team/image/405/edward-gaming-52bsed1a.png",
        "imagen2": "https://cdn.pandascore.co/images/team/image/411/invictus_gaminglogo_square.png",
        "Torneo": "LPL",
        "votosA": 107,
        "votosB": 70,
        "Porcentaje": 60.451977401129945,
        "Fecha": "2023-04-21T00:00:00.000Z",
        "Deporte": "League of Legends",
        "__v": 0
    },
    {
        "_id": "662559e3cefaea3b1735c36b",
        "juego": "TES-RW",
        "equipo1": "TES",
        "equipo2": "RW",
        "imagen1": "https://cdn.pandascore.co/images/team/image/126059/top_esportslogo_square.png",
        "imagen2": "https://cdn.pandascore.co/images/team/image/1569/rogue_warriorslogo_square.png",
        "Torneo": "LPL",
        "votosA": 75,
        "votosB": 25,
        "Porcentaje": 75,
        "Fecha": "2023-04-21T00:00:00.000Z",
        "Deporte": "League of Legends",
        "__v": 0
    },
    {
        "_id": "662559f4cefaea3b1735c36d",
        "juego": "FPX-SN",
        "equipo1": "FPX",
        "equipo2": "SN",
        "imagen1": "https://cdn.pandascore.co/images/team/image/1568/fun_plus_phoenixlogo_square.png",
        "imagen2": "https://cdn.pandascore.co/images/team/image/652/_.png",
        "Torneo": "LPL",
        "votosA": 30,
        "votosB": 11,
        "Porcentaje": 73.17073170731707,
        "Fecha": "2023-04-21T00:00:00.000Z",
        "Deporte": "League of Legends",
        "__v": 0
    },
    {
        "_id": "66255a04cefaea3b1735c36f",
        "juego": "RNG-JDG",
        "equipo1": "RNG",
        "equipo2": "JDG",
        "imagen1": "https://cdn.pandascore.co/images/team/image/74/royal-never-give-up-cyacqft1.png",
        "imagen2": "https://cdn.pandascore.co/images/team/image/318/qg-reapers.png",
        "Torneo": "LPL",
        "votosA": 190,
        "votosB": 202,
        "Porcentaje": 48.46938775510204,
        "Fecha": "2023-04-21T00:00:00.000Z",
        "Deporte": "League of Legends",
        "__v": 0
    }
]