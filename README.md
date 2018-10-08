# WebScraping

## Objetivo

El objetivo de este c�digo es realizar webscraping a la p�gina "http://informacioninteligente10.xm.com.co/transacciones/Paginas/HistoricoTransacciones.aspx" 
que contiene archivos en formato xls.

Se realiz� un breve estudio del DOM (Document Object Model) con la finalidad de extraer las URLs esenciales.

###Requisitos:

Es preciso tener instalado Python version 3.7.0 y las librerias requests, bs4 y urllib.request.

Para instalar las librerias de Python en Windows es preciso instalar pip des la consola de Windows mediante:

    python get-pip.py

Luego escribir:

    ``` pip install bs4
    urllib.request ```

Esta es una versi�n en desarrollo. Se est�n afinando los par�metros para sincronizar la solicitud realizada al servidor 
con su respuesta de modo que este no interprete el continuo n�mero de solicitudes con un ataque.   


###Instrucciones

Para ejecutarlo localmente es preciso cambiar la variable OUTPUT_DIR a la direcci�n deseada