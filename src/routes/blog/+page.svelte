<script>
    import qaraNohur from "../../media/qaraNohur.jpg";
    import Container from "../../components/container.svelte";
    let holder =
        "Azərbaycanın İsmayıllı rayonu ərazisində yerləşən yüksək dağ gölü. İsmayıllı şəhərindən 8 km şimal-şərqdə yerləşir. Dəniz səviyyəsindən 1520 m yüksəklikdə yerləşir. Böyük Qafqaz dağlarından axan Qaranohur çayının hövzəsinə daxildi";
</script>

<svelte:head>
    <title>Home Page Outline</title>
    <meta name="description" content="a personal blog" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&family=Roboto:wght@300;400;500;700;900&display=swap"
        rel="stylesheet"
    />
</svelte:head>
<div class="min-h-screen">
    <div class="flex justify-center items-center h-screen flex-wrap">
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
        <Container
            link="/"
            src={qaraNohur}
            alt="Qara Nohur gölü"
            text={holder}
        />
    </div>
</div>
