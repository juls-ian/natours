## SHAPE OUTLINE OF IMAGE

.header {
    height: 95vh;
    background-image: linear-gradient(to right bottom, rgba(110, 231, 183, 0.604), rgba(4, 120, 87, 0.725)), url("../images/hero.jpg");
    background-size: cover;
    background-position: top;
    /* adding the shape outline */
    clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%);
}

## CSS Animations
.heading-primary-main {
    display: block;
    font-size: 60px;
    font-weight: 400;
    letter-spacing: 35px;
    animation-name: moveInLeft;
    animation-duration: 1s;
    a
}

@keyframes moveInLeft {
    0% {
        opacity: 0;
        transform: translateX(-100px);
    }

    /* steps */
    80% {
        transform: transformX(10px);
    }

    100% {
        opacity: 1;
        transform: translate(0);
    }
}