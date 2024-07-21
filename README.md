<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Arini & Rafi Wedding</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">


    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Castoro:ital@0;1&family=Nanum+Pen+Script&family=Sacramento&display=swap" rel="stylesheet">

    <!-- simplyCountdown -->

    <link rel="stylesheet" href="countdown/simplyCountdown.theme.default.css" />
    <script src="countdown/simplyCountdown.min.js"></script>


    <link rel="stylesheet" href="style.css">
</head>


<body>


    <section id="hero" class="hero w-100 h-100 p-3 mx-auto text-center d-flex
    justify-content-center align-items-center text-white">
        <main>
            <h4>Kepada Bapak/Ibu/Saudara/i,</h4>
            <h1>Arini Aisyah & Muhammad Rafi</h1>
            <p>Akan melangsungkan resepsi pernikahan dalam :</p>
            <div class="simply-countdown"></div>
            <a href="#undangan" class="btn btn-lg mt-4">Lihat Undangan</a>
        </main>
    </section>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>

    <script>
        simplyCountdown('.simply-countdown', {
            year: 2023, // required
            month: 9, // required
            day: 30, // required
            hours: 9, // Default is 0 [0-23] integer
            minutes: 0, // Default is 0 [0-59] integer
            seconds: 0, // Default is 0 [0-59] integer
            words: { //words displayed into the countdown
                days: {
                    singular: 'hari',
                    plural: 'days'
                },
                hours: {
                    singular: 'jam',
                    plural: 'hours'
                },
                minutes: {
                    singular: 'menit',
                    plural: 'minutes'
                },
                seconds: {
                    singular: 'detik',
                    plural: 'seconds'
                }
            },

        });
    </script>
</body>

</html>
