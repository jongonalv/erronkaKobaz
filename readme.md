## ERP Sistema
KOBAZ enpresako programatzaileak egin duten software / sistema birtuala ERP sistema bat garatzeko

## Makina birtual nagusiak

- Sistema birtualeko makina / funtzio nagusiak:

    - ERP Sistema: odoo makina birtual bat.
    - Web zerbitzaria: nginx (webgunea ezartzeko)
    - Datu basea: POSTGRES.
    - Backup zerbitzaria: Duplicati makina birtuala.

## Enpresako webgune nagusia

Karpeta bat dago "web" izenekoa, produktua saltzeko erabiliko den webgunea erabiltzeko

    - HTML fitxategiak (Web-aren egitura eta informazioa)
    - CSS fitxategia (webgunearen estiloa jartzeko)

## Nola abiarazi sistema

docker-compose.yml fitxategia, sortutako sistema edozein ekipotan jartzeko balio du.

    1. Lehenik eta behin, github repositoriotik proiektua deskargatu: https://github.com/jongonalv/erronkaKobaz.git
    2. Barruan, docker-compose fitxategia konprobatu
    3. Zure sisteman docker egon behar du instalatuta.
    4. Powershell erabiliz, fitxategiaren kokapenera joango gara "cd ..." erabiliz
    5. fitxategiaren barruan, "docker-compose up -d" komandoa erabiliz, sistema martxan jarriko da