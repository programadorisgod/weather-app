<script>
    import search_svg from '$lib/svg/search.svg';
    import iconWeather from '$lib/svg/iconWeather.svg';
    import  youtube from '$lib/svg/youtube.svg';
    import instagram from '$lib/svg/instagram.svg';
    import github from '$lib/svg/github.svg';
    import realtime from '$lib/svg/realtime.svg';
    import forecast from '$lib/svg/forecast.svg';
    import sports from '$lib/svg/sports.svg';

</script>

<header>

    <h3>YOU ARE IN 🇨🇴</h3>

    <input type="text" name="search_country" placeholder="Search country">
    <button>
         <img src={search_svg} alt="button_search">
    </button>

</header>

<aside>
    
    <div>
        <h3>Weather</h3>
         <img src={iconWeather} alt="icon_weather">
    </div>

    <div>
        <ul>
            <li>
                <img src={realtime} alt="realtime_icon">
                RealTime                
            </li>

            <li>
                <img src={forecast} alt="forecast_icon">
                Forecast
            </li>

            <li>
                <img src={sports} alt="sports_icon">
                Sports
            </li>
        </ul>
    </div>

    <footer>
        <img src={github} alt="github_icon">
        <img src={instagram} alt="instagram_icon">
        <img src={youtube} alt="youtube_icon">
    </footer>
</aside>


<main>
    <slot> </slot>
</main>