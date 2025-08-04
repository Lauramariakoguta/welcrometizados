body {
    color: light pink;
    background: purple;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
    border-bottom: solid 2px rgb(128, 0, 128);
    padding: 20px;
    font-size: 32px;
    color: rgb(255, 182, 193);
}

.chamada {
    background: rgb(255,203,217);
    padding-bottom: 90px;
    padding-top: 90px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 10%;
}

h1 {
    font-size: 30px;
}

p {
    font-size: 20px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}

.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}


<html lang="pt-BR">

<cabeça>
    <link rel="folha de estilo" href="estilos.css">
    <link rel="pré-conexão" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="folha de estilo">
    <título>Guiminamflix</título>
</cabeçalho>

<corpo>
    <cabeçalho>NOSTAL_GIMFLIX</cabeçalho>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>GRANDES SUCESSOS ESQUECIDOS DOS ANOS 2000</h1>
            <p>#Gi_nostálgico</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/watch?v=VD2jgcBJQmk&t=587s"
                título="Player de vídeo do YouTube" frameborder="0"
                allow="acelerômetro; reprodução automática; gravação na área de transferência; mídia criptografada; giroscópio; imagem em imagem; compartilhamento na web"
                referrerpolicy="origem-estrita-quando-origem-cruzada" allowfullscreen></iframe>
        </div>
    </seção>

    <seção class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=SJlIpsoz1aY">
                <img src="youtube.com/watch?v=tgdlESKWww0" />
            </a>
            <a href="https://www.youtube.com/watch?v=OqWbF-o2VbI">
                <img src="https://www.youtube.com/watch?v=qBy03lMOEiw" />
            </a>
            <a href="https://www.youtube.com/watch?v=219c2UFN3hU">
                <img src="https://www.youtube.com/watch?v=gVeZK0Fv4qg" />
            </a>
            <a href="https://www.youtube.com/watch?v=TD3UV-sceOA&t=711s">
                <img src="https://www.youtube.com/watch?v=iw_AREUaNTo" />
            </a>
            <a href="https://www.youtube.com/watch?v=EJRmKa0MJAM">
                
            </a>
        </div>
    </seção>

</corpo>

</html>
.categoria h2 {
    color: rgb(0, 0, 128);
}
