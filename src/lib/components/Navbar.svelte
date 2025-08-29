<script lang="ts">

</script>

<nav class="main-navbar">
    <ul>
        <li><a href="#Home" aria-label="home-ref">Home</a></li>
        <li><a href="#About" aria-label="about-ref">About Me</a></li>
        <li><a href="#Skills" aria-label="skills-ref">Skills</a></li>
        <li><a href="#Projects" aria-label="projects-ref">Projects</a></li>
        <li><a href="#Contact" aria-label="contact-ref">Contact Me</a></li>
    </ul>
</nav>

<style>
    .main-navbar {
        background-color: #222;
        color: white;
    }

    .main-navbar ul {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
    }

    .main-navbar li a {
        display: block;
        padding: 1rem;
        color: white;
        text-decoration: none;
    }

    .main-navbar li a:hover {
        background-color: #444;
    }

    /* Mobile / small screen: sidebar layout */
    @media (max-width: 768px) {
        .main-navbar {
            height: 100vh;
            width: 200px;
            position: fixed;
            top: 0;
            left: 0;
        }

        .main-navbar ul {
            flex-direction: column;
            align-items: flex-start;
            padding-top: 2rem;
        }

        .main-navbar li a {
            width: 100%;
            padding: 1rem 2rem;
        }
    }

    /* Large screen: top navbar layout */
    @media (min-width: 769px) {
        .main-navbar {
            width: 100%;
            position: relative;
        }

        .main-navbar ul {
            flex-direction: row;
        }
    }
</style>
