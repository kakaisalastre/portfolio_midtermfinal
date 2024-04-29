# portfolio_midtermfinal
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="style.css" />
    <title>Web Design Mastery | Responsive Portfolio</title>
</head>
<body>
    <nav>
        <div class="nav__content">
            <div class="logo"><a href="#">Khyla</a></div>
            <label for="check" class="checkbox">
                <i class="ri-menu-line"></i>
            </label>
            <input type="checkbox" name="check" id="check">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Portfolio</a></li>  
                <li><a href="#">Contact</a></li> 
            </ul> 
        </div>
    </nav>
    <section class="section">
        <div class="section__container">
            <div class="content">
                <p class="subtitle">HELLO</p>
                <h1 class="title">
                    I'm <span>Khyla<br>a</span> Web Developer
                </h1>
                <section id="About" class="section">
                    <div class="section__container">
                    <h2 class="section_title">About Me</h2>
                <p class="description">
                    Welcome to my web developer portfolio! I'm Khyla, a skilled and creative web developer with a passion for creating beautiful, responsive, and user-friendly websites, I've worked on a variety of web projects, ranging from personal blogs to e-commerce platforms.
                </p>
                <div class="action__btns">
                </div>
            </div>
            <div class="image">
                <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/440139778_454213797169707_1714795442042345566_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGpdb6jbzYHoN5F7l9P5IsCpm7mTiMJo7KmbuZOIwmjsmx50phD39AbjxZj3gbZgf4UfczLqs9I5BpvMhr2JL0w&_nc_ohc=FpcWWieUBcIQ7kNvgE3aPt9&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QGRb8ynJsQ-DNv13orwecSunWbzy6GwgopkfA-Lccn6tg&oe=665607CB" alt="profile"/>
        </div>
    </section>

    <section id="skills" class="section">
        <div class="section_container">
            <div class="content">
                <h2 class="section_title">Skills</h2>
                <div class="skill">
                    <div class="name">HTML</div>
                    <div class="progress-bar">
                        <div class="progress" id="htmlProgress" style="width: 80%;"></div>
                        <div class="percent" id="htmlPercent">80%</div>
                    </div>
                    <section class="skills">
                        <div class="container">
                            <div class="skill">
                                <div class="name">CSS</div>
                                <div class="progress-bar">
                                    <div class="progress" id="cssProgress" style="width: 50%;"></div>
                                    <div class="percent" id="cssPercent">50%</div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">JavaScript</div>
                                <div class="progress-bar">
                                    <div class="progress" id="jsProgress" style="width: 80%;"></div>
                                    <div class="percent" id="jsPercent">70%</div>
                                </div>
                            </div>
                        </div>
                    </section>

                    <section id="portfolio" class="section">
                        <div class="section_container">
                            <h2 class="sub-title">Portfolio</h2>
                            <span>My Recent Work</span>
                            <div class="work-list">
                                <div class="work">
                                    <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/440108759_405095535714649_215878164779112245_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEaVdRiNtBKhPWk_w2HI9zPbcrXLD8GJYxtytcsPwYljDRS18Ku8Vl5t23DvmVLnB1Blnu8Oulz1CHbtx58B2KV&_nc_ohc=BUjJfM-QXRkAb66L63N&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QHEjDf1tMm2qMPpE2SYna_RaOhSnxeCYKqapc9-wjbxYg&oe=664E983A" alt="Work 1">
                                    <div class="layer"></div>
                                </div>
                                <div class="work">
                                    <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/438231556_724005092983111_1110513058503303807_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFtj_mDOKsrCO2ZYpoTlBYvfQk2TPOpaw99CTZM86lrD2RmIJZk3ss3fnBFr-ueOIFk4V44pldPB_yiRs1Gn4dj&_nc_ohc=3KWOxiXCdYsAb74VT5h&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QHv4pgUHjmeCIi4ubKSr6HEOlcMfP-MzL8iecaMTmTeew&oe=664E9E0D" alt="Work 2">
                                    <div class="layer"></div>
                                </div>
                                <div class="work">
                                    <img src="https://scontent.fmnl17-4.fna.fbcdn.net/v/t1.15752-9/437970774_965712794923191_2832052138953689055_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGicw9mLZZOG5XtgTFh4Y6BUfuU3oYOjaBR-5Tehg6NoCctPctO4xjLosC5-MTSD-9zGOjFJG50c0j3dXgdsAtU&_nc_ohc=nnXXJ_iA_E0Q7kNvgG21bLO&_nc_ht=scontent.fmnl17-4.fna&oh=03_Q7cD1QH9IY_lE3awy_EHyJJ-_GaaO2IGi1AStcvPgcl_HE5qSg&oe=664EF65A" alt="Work 3">
                                    <div class="layer"></div>
                                </div>
                            </div>
                        </div>
                    </section>

                    <section id="contact" class="section">
                        <div class="section_container">
                            <div class="row">
                                <div class="contact-left">
                                    <h1 class="section_title">Contact Me</h1>
                                    <p><i class="ri-mail-line"></i> khylabautista02@email.com</p>
                                    <p><i class="ri-phone-line"></i> +639298780830</p>
                                    <p><i class="ri-map-pin-line"></i> Las Pinas Talon Tres, Urbanville</p>
                                </div>
                                <div class="contact_form">
                                    <form action="https://api.web3forms.com/submit" method="POST">
                                        <input type="hidden" name="access_key" value="20579234-aab0-4b11-8164-3c15f91dcd37">
                                        <input type="text" name="name" placeholder="Your Name">
                                        <input type="email" name="email" placeholder="Your Email">
                                        <textarea name="message" placeholder="Your Message"></textarea>
                                        <button type="submit">Send Message</button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </section>
                    <style>
                    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

:root {
    --primary-color: #a855f7;
    --primary-color-dark: #9333ea;
    --secondary-color: #ca8a04;
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --extra-light: #faf5ff;
    --max-width: 1200px;
}

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

a {
    text-decoration: none;
}

body {
    font-family: "Poppins", sans-serif;
}

nav {
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    background-color: #ffffff;
    z-index: 99;
}

.nav_content {
    max-width: var(--max-width);
    margin: auto;
    padding: 1.5rem 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

nav .logo a {
    font-size: 1.5rem;
    font-weight: 600;
    color: var(--primary-color);
    transition: .3s;
}

nav .logo a:hover {
    color: var(--primary-color-dark);
}

nav .checkbox {
    display: none;
}

nav input {
    display: none;
}

nav .checkbox i {
    font-size: 2rem;
    color: var(--primary-color);
    cursor: pointer;
}

ul {
    display: flex;
    align-items: center;
    gap: 1rem;
    list-style: none;
    transition: left 0.3s;
}

ul li a {
    padding: 1rem;
    border: 2px solid transparent;
    text-decoration: none;
    font-weight: 600;
    color: var(--text-dark);
    transition: 0.3s;
}

ul li a:hover {
    border-color: var(--secondary-color);
    color: var(--secondary-color);
}

.section {
    background-color: var(--extra-light);
}

.section_container {
    min-height: 100vh;
    max-width: var(--max-width);
    margin: auto;
    padding: 1rem;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 4rem;
}

.subtitle {
    letter-spacing: 2px;
    font-weight: 400;
    line-height: 3rem;
    color: var(--text-dark);
    margin-bottom: 1rem;
}

.title span {
    font-weight: 600;
}

.description {
    line-height: 1.5rem;
    margin-bottom: 2rem;
}

.action__btns {
    display: flex;
    gap: 1rem;
}

.action__btns button {
    font-size: 1rem;
    font-weight: 600;
    letter-spacing: 2px;
    padding: 1rem 2rem;
    outline: none;
    border: 2px solid var(--primary-color);
    border-radius: 10px;
    transition: 0.3s;
    cursor: pointer;
}

.hire__me {
    background-color: var(--primary-color);
    color: #ffffff;
}

.hire__me:hover {
    background-color: var(--secondary-color);
}

.portfolio {
    color: var(--primary-color);
}

.image {
    display: grid;
    place-items: center;
}

.image img {
    max-width: 25rem;
    border-radius: 50%;
}

.portfolio:hover {
    background-color: var(--primary-color-dark);
    color: #ffffff;
}

.content {
    display: flex;
    flex-direction: column;
    justify-content: center;
}

@media (max-width: 750px) {
    nav .checkbox {
        display: block;
    }

    ul {
        position: absolute;
        width: 100%;
        height: calc(100vh - 85px);
        left: -100%;
        top: 85px;
        background-color: var(--extra-light);
        flex-direction: column;
        justify-content: center;
        gap: 3rem;
    }

    nav #check:checked ~ ul {
        left: 0;
    }

    ul li a {
        font-size: 1.25rem;
    }

    .section__container {
        padding: 10rem 1rem 5rem 1rem;
        text-align: center;
        grid-template-columns: repeat(1, 1fr);
    }

    .image {
        grid-area: 1/1/2/2;
    }

    .action__btns {
        margin: auto;
    }
}

.skill {
    margin-bottom: 20px;
}

.name {
    font-weight: bold;
    color: #90EE90;
}

.progress-bar {
    display: flex;
    align-items: center;
    width: 100%;
    background-color: #f0f0f0;
    border-radius: 5px;
    overflow: hidden;
}

.progress {
    height: 30px;
    background-color: #90EE90;
    color: white;
    text-align: center;
    line-height: 30px;
    transition: width 0.5s ease;
}

#portfolio {
    padding: 50px 0;
}

.work-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}

.work {
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}

.work img {
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}

.layer {
    width: 100%;
    height: 0;
    background: linear-gradient(rgba(0,0,0,0.6), #03ad28);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;
}

.layer h3 {
    font-weight: 500;
    margin-bottom: 20px;
}

.layer a {
    margin-top: 20px;
    color: #03ad28;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}

.work:hover img {
    transform: scale(1.1);
}

.work:hover .layer {
    height: 100%;
}

.btn {
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #03ad28;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
    transition: background 0.5s;
}

.btn:hover {
    background: #ff004f;
}

.contact-left {
    flex-basis: 35%;
}

.contact-right {
    flex-basis: 60%;
}

.contact-left p {
    margin-top: 30px;
}

.header-text {
    margin-top: 20%;
    font-size: 30px;
}

.header-text h1 {
    font-size: 60px;
    margin-top: 20px;
}

.section-title {
    font-size: 60px;
    font-weight: 600;
    color: #080808;
}


