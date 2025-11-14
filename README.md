# piza-solucoes-residenciais

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piza Soluções Residenciais</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5faff;
        }

        /* Paleta */
        :root {
            --azul-escuro: #0a2a43;
            --azul-claro: #4aa8ff;
        }

        /* Header */
        header {
            background: var(--azul-escuro);
            color: white;
            display: flex;
            align-items: center;
            padding: 20px;
            justify-content: space-between;
        }

        .logo {
            display: flex;
            align-items: center;
            font-size: 24px;
            font-weight: bold;
        }

        .logo svg {
            width: 40px;
            margin-right: 10px;
            fill: white;
        }

        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }

        /* Banner */
        .banner {
            background: url('https://images.unsplash.com/photo-1581091012184-5c1d64b32a06?auto=format&fit=crop&w=1500&q=80') center/cover no-repeat;
            height: 420px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 6px #000;
        }

        .banner h1 {
            font-size: 48px;
        }

        /* Seções */
        section {
            padding: 50px 10%;
        }

        h2 {
            color: var(--azul-escuro);
            margin-bottom: 20px;
        }

        .servicos {
            display: flex;
            justify-content: space-between;
            gap: 25px;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            border-radius: 8px;
            width: 31%;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            border-radius: 8px 8px 0 0;
        }

        .card div {
            padding: 15px;
        }

        /* Contato */
        .contato {
            background: var(--azul-escuro);
            color: white;
            text-align: center;
            padding: 40px 10%;
        }

        .contato a {
            color: var(--azul-claro);
            font-weight: bold;
            text-decoration: none;
            font-size: 20px;
        }

        /* Rodapé */
        footer {
            background: #061a29;
