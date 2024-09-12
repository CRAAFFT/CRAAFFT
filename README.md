<h1 align="center"> KnowRise </h1> <br>
<p align="center">
    <img alt="GitPoint" title="GitPoint" src="https://th.bing.com/th/id/OIP.n4eE549GEDLSzK--Te_TTAHaEK?rs=1&pid=ImgDetMain" width="450">
</p>

<style>
    body{
    background: #1E2742;
    box-sizing: border-box;
}
.container-dev{
    display: grid;
    place-content: center;
    min-height: 100vh;
}
input[type="radio"] {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border-width: 0;
}

p{
    position: absolute;
    bottom: 2rem;
    right: 2rem;
    color: white;
    font-size: 0.8rem;
}

.circle-wrapper{
border: 1px solid #0f3e5d;
position: relative;
border-radius: 9999px;
display: grid;
width: 450px;
height: 450px;
grid-template-areas: "stack";
place-content: center;
}

label{
    grid-area: stack;
    width: 5rem;
    height: 5rem;
    border-radius: 9999px;
    border: 1px solid #738088;
    display: grid;
    background-color: rgba(255, 255, 255, 0.2);
    position: relative;
    color: #87ceeb;
    font-size: 1.25rem;
    transition-property: all;
    transition-duration: 0.5s;
    cursor: pointer;
    box-shadow: 0 0 0 4px rgba(255, 255, 255, 0.2);
}
img{
    border-radius: 9999px;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: all 1s ease-in-out;
}
svg{
    transition: all 0.5s ease-in-out;
    position: absolute;
    inset: 0 0 0 -25%;
    margin: auto;
    width: 125px;
    opacity: 0;
    z-index: -10;
}

.center-elemental{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: auto;
    width: 8rem;
    height: 8rem;
    background-color: #1b2c36;
    border: 1px solid rgba(255, 255, 255, 0.4);
    border-radius: 50%;
    display: grid;
    place-content: center;
    text-transform: uppercase;
    font-weight: 100;
    letter-spacing: 0.05em;
    color: #cbd5e0;
    font-size: 1.125rem;
}
.center-elemental::before{
    content: "";
    position: absolute;
    top: -1px;
    right: -1px;
    bottom: -1px;
    left: -1px;
    background-color: #0a4368;
    border-radius: 50%;
    z-index: -10;
    transition: all 1s;
}
input:checked + label {
transform: none !important;
transition-duration: 1s;
}
input:checked + label > img{
    transform: scale(2);
}
input:checked + label > svg {
    opacity: 1;
    transform: scale(2.25) rotate(45deg);
    transition-delay: 700ms, 500ms, 2000ms;
}

.avatar{
    --radius: 14rem;
    --d: calc(var(--i) / var(--total));
    --r-offset: -0.15turn;
    --r-amount: 1turn;
    --r: calc((var(--r-amount) * var(--d)) + var(--r-offset));
    transform: rotate(var(--r)) translate(var(--radius)) rotate(calc(-1 * var(--r)));
}
</style>
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
