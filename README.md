<h1 align="center"> KnowRise </h1> <br>
<p align="center">
    <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
</p>
<div class="container-dev">
<div style="--total:5" class="circle-wrapper">
    <div class="center-elemental">The Team</div>

    <input type="radio" name="radio-avatar" id="radio-avatar-1">
    <label id="avatar-1" for="radio-avatar-1" class="avatar" style="--i:1">
        <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
        <svg viewBox="0 0 300 300">
            <text fill="currentColor">
                <textPath xlink:href="#circlePath">Azzello Fabian Cristoper A.K.A Ello - Web Frontend</textPath>
            </text>
        </svg>
    </label>

    <input type="radio" name="radio-avatar" id="radio-avatar-2">
    <label id="avatar-2" for="radio-avatar-2" class="avatar" style="--i:2">
        <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
        <svg viewBox="0 0 300 300">
            <text fill="currentColor">
                <textPath xlink:href="#circlePath">Muhammad Rifaa Siraajuddin .S A.K.A KnowRise - Web Backend</textPath>
            </text>
        </svg>
    </label>

    <input type="radio" name="radio-avatar" id="radio-avatar-3">
    <label id="avatar-3" for="radio-avatar-3" class="avatar" style="--i:3">
        <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
        <svg viewBox="0 0 300 300">
            <text fill="currentColor">
                <textPath xlink:href="#circlePath">Muhamad Hilal A.K.A M1zaru - Backend API System</textPath>
            </text>
        </svg>
    </label>

    <input type="radio" name="radio-avatar" id="radio-avatar-4">
    <label id="avatar-4" for="radio-avatar-4" class="avatar" style="--i:4">
        <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
        <svg viewBox="0 0 300 300">
            <text fill="currentColor">
                <textPath xlink:href="#circlePath">Nadhif Musyafa Alfarel A.K.A TreeAngel - Android Developer</textPath>
            </text>
        </svg>
    </label>

    <input type="radio" name="radio-avatar" id="radio-avatar-5">
    <label id="avatar-5" for="radio-avatar-5" class="avatar" style="--i:5">
        <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
        <svg viewBox="0 0 300 300">
            <text fill="currentColor">
                <textPath xlink:href="#circlePath">Bintang Akbar Ramadhan A.K.A Biboo - Desktop Developer</textPath>
            </text>
        </svg>
    </label>
</div>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 300 300" width="0" height="0">
    <defs>
        <path id="circlePath" d="M 150, 150 m -100, 0 a 100,100, 0 0,1 200,0 a 100,100 0 0,1 -200,0" />
    </defs>
</svg>
</div>
<script>
    document.querySelectorAll('input[type="radio"]').forEach(radio => {
    radio.addEventListener('click', (e) => {
        e.preventDefault();
        setTimeout(() => radio.checked = !radio.checked, 0);
    });
});
</script>
