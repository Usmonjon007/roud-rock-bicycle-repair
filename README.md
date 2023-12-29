<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roud Rock Bicycle Repair :: Usmonjon Hasanov</title>
    <link rel="stylesheet" href="./style.css">
    <meta name="author" content="Usmonjon Hasanov">
    <meta name="title" content="LaslesVPN :: Usmonjon Hasanov">
    <meta name="description" content="LaslesVPN website created by Usmonjon Hasanov">
    <meta name="image" content="./images/preview.png">
    <meta name="image:width" content="1268">
    <meta name="image:height" content="779">
    <meta name="og:title" content="LaslesVPN :: Usmonjon Hasanov">
    <meta name="og:description" content="LaslesVPN website created by Usmonjon Hasanov">
    <meta name="og:image" content="./images/preview.png">
    <meta name="og:image:width" content="1268">
    <meta name="og:image:height" content="779">
    <style>
      @import url('./font.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&family=Vampiro+One&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'TT Hoves';
}

html {
    scroll-behavior: smooth;
}

/* container */
.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
}

/* containerend */

/* home */
.home {
    padding: 50px 0 280px 0;
    background: url('./images/bg-full.png') no-repeat;
    background-size: cover;
    background-position: right top;
}

.home .container,
.home .container .bottom {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-direction: column;
    gap: 190px;
}

.home .container .logo img {
    width: 419.31px;
}

.home .container .bottom {
    gap: 29px;
}

.home .container .bottom .title {
    color: var(--Gray-1, #333);
    font-size: 47px;
    font-weight: 700;
    line-height: 100.5%;
}

.home .container .bottom .title span:first-child {
    color: #E15252;
    font-size: 36px;
    font-weight: 500;
    line-height: 0%;
}

.home .container .bottom .desc {
    color: var(--Gray-1, #333);
    font-size: 14px;
    font-weight: 500;
}

.home .container .bottom .btn {
    color: #FFF;
    text-align: center;
    font-size: 18px;
    font-weight: 700;
    text-decoration: none;
    padding: 12px 44px;
    border-radius: 42px;
    background: #E15252;
    border: 2px solid transparent;
    transition: all .3s ease;
}

.home .container .bottom .btn:hover,
.home .container .bottom .btn:focus {
    background: #FFFFFF;
    color: #E15252;
    border-color: #E15252;
}

/* home end */

/* services */
.services {
    padding: 0 0 50px 0;
}

.services .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 52px;
}

.services .container .top {
    padding: 100px;
    border-radius: 0px 0px 50px 50px;
    background: var(--Gray-6, #F2F2F2);
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 10px;
}

.services .container .top>.title {
    color: var(--Gray-1, #333);
    text-align: center;
    font-size: 64px;
    font-weight: 700;
}

.services .container .top>.desc {
    color: #E15252;
    text-align: center;
    font-size: 18px;
    font-weight: 500;
}

.services .container .bottom {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 50px;
}

.services .container .bottom .services-list {
    width: 100%;
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.services .container .bottom .services-list .services-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 8px;
}

.services .container .bottom .services-list .services-item img {
    width: 200px;
    border: 12px solid #E15252;
    border-radius: 9999px;
}

.services .container .bottom .services-list .services-item .text {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 10px;
}

.services .container .bottom .services-list .services-item .text .sub-title {
    color: var(--Gray-1, #333);
    text-align: center;
    font-size: 18px;
    font-weight: 700;
}

.services .container .bottom .services-list .services-item .text .desc {
    color: var(--Gray-2, #4F4F4F);
    text-align: center;
    font-size: 14px;
    font-weight: 500;
}

.services .container .bottom .btn {
    text-decoration: none;
    color: #FFF;
    text-align: center;
    font-size: 18px;
    font-weight: 700;
    padding: 12px 28px;
    border-radius: 42px;
    background: #E15252;
    box-shadow: 0px 4px 20px 0px rgba(225, 82, 82, 0.50);
    transition: all .3s ease;
    border: 2px solid transparent;
}

.services .container .bottom .btn:hover,
.services .container .bottom .btn:focus {
    background: #FFFFFF;
    color: #E15252;
    border-color: #E15252;
}

/* services end */

/* about */
.about {
    padding: 50px 0 0 0;
    background: url('./images/bg.png'), #E15252;
}

.about .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 50px;
}

.about .container>.text {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 5px;
}

.about .container>.text .title {
    color: #FFF;
    text-align: center;
    font-size: 64px;
    font-weight: 700;
}

.about .container>.text .desc {
    color: var(--Gray-1, #333);
    text-align: center;
    font-size: 18px;
    font-weight: 500;
}

.about .container .content {
    width: 100%;
    background: #FFFFFF;
    overflow: hidden;
    border-radius: 50px 50px 0px 0px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 648px;
}

.about .container .content .left {
    width: 469px;
    background: url('./images/about.png') no-repeat;
    background-size: cover;
    background-position: bottom;
    height: 648px;
}

.about .container .content .right {
    width: calc(100% - 469px);
    padding: 0 30px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-direction: column;
    gap: 30px;
}

.about .container .content .right .text {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-direction: column;
    gap: 20px;
}

.about .container .content .right .text .top {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-direction: column;
    gap: 22px;
}

.about .container .content .right .text .top .title {
    color: var(--Gray-1, #333);
    font-size: 46px;
    font-weight: 400;
    font-family: 'Vampiro One', sans-serif;
}

.about .container .content .right .text .top span {
    display: inline-block;
    width: 90px;
    height: 2px;
    border-radius: 1px;
    background: #E15252;
}

.about .container .content .right .text .desc {
    color: var(--Gray-2, #4F4F4F);
    font-size: 14px;
    font-weight: 500;
}

.about .container .content .right .btn {
    text-decoration: none;
    color: #FFF;
    text-align: center;
    font-size: 18px;
    font-weight: 700;
    padding: 12px 28px;
    border-radius: 42px;
    background: #E15252;
    box-shadow: 0px 4px 20px 0px rgba(225, 82, 82, 0.50);
    transition: all .3s ease;
    border: 2px solid transparent;
}

.about .container .content .right .btn:hover,
.about .container .content .right .btn:focus {
    background: #FFFFFF;
    color: #E15252;
    border-color: #E15252;
}

/* about end */

/* contact */
.contact {
    padding: 0 0 50px 0;
    background: url('./images/bg-other.png') no-repeat;
    position: relative;
}

.contact::before {
    position: absolute;
    content: "";
    width: 100%;
    height: 100%;
    background: #FFFFFF80;
    z-index: 0;
}

.contact .content {
    padding: 100px 110px 140px 110px;
    width: 100%;
    position: relative;
    z-index: 1;
    background: #E15252;
    border-radius: 0px 0px 50px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 50px;
}

.contact .content .text {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 5px;
}

.contact .content .text .title {
    color: #FFF;
    text-align: center;
    font-size: 64px;
    font-weight: 700;
}

.contact .container .text .desc {
    color: var(--Gray-1, #333);
    text-align: center;
    font-size: 18px;
    font-weight: 500;
}

.contact .container .bottom {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 100px;
}

.contact .container .bottom .form {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    flex-direction: column;
    gap: 14px;
}

.contact .container .bottom .form input {
    width: 374px;
    height: 56px;
    padding: 20px;
    border: none;
    outline: none;
    color: #E15252;
    border-radius: 51px;
    font-size: 18px;
    background: #FFF;
}

.contact .container .bottom .form input::placeholder {
    font-size: 18px;
}

.contact .container .bottom .form button {
    width: 168px;
    height: 56px;
    padding: 20px;
    border: none;
    outline: none;
    color: #FFF;
    border-radius: 51px;
    font-size: 18px;
    border: 3px solid #FFF;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    background: transparent;
    transition: all .3s ease;
}

.contact .container .bottom .form button:hover,
.contact .container .bottom .form button:focus {
    background: #FFFFFF;
    color: #E15252;
}

.contact .container .bottom .data {
    margin-top: 32px;
    width: 100%;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.contact .container .bottom .data .list {
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-direction: column;
    gap: 30px;
}

.contact .container .bottom .data .list .item {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 20px;
    color: #FFF;
    font-size: 14px;
    font-weight: 500;
}

.contact .container .bottom .data .list .item svg {
    width: 24px;
}

/* contact end */
    </style>
</head>

<body>
    <!-- home -->
    <section id="home" class="home">
        <div class="container">
            <a href="#" class="logo" title="logo">
                <img src="./images/logo-svg.svg" alt="">
            </a>
            <div class="bottom">
                <h2 class="title">
                    <span>What is Lorem Ipsum</span>
                    <br />
                    <span>What is Lorem Ipsum</span>
                </h2>
                <p class="desc">Lorem Ipsum is simply dummy text of the printing and typesetting<br />industry. Lorem
                    Ipsum has been the industry's standard dummy<br />text ever since the 1500s, when an unknown printer
                    took a galley of<br />type and
                    scrambled it make a type specimen book.</p>
                <a href="#" class="btn">Help Me</a>
            </div>
        </div>
    </section>
    <!-- home end -->

    <!-- services -->
    <section id="services" class="services">
        <div class="container">
            <div class="top">
                <h2 class="title">Services for you</h2>
                <p class="desc">Repair and maintenance</p>
            </div>
            <div class="bottom">
                <ul class="services-list">
                    <li class="services-item">
                        <img src="./images/service-1.png" alt="Service">
                        <div class="text">
                            <h2 class="sub-title">Diagnosis and adjustment<br />of the bike</h2>
                            <p class="desc">Lorem Ipsum is simply dummy text of<br />the printing and typesetting
                                industry.<br />Lorem Ipsum has been the industry's<br />standard
                                dummy text</p>
                        </div>
                    </li>
                    <li class="services-item">
                        <img src="./images/service-2.png" alt="Service">
                        <div class="text">
                            <h2 class="sub-title">Diagnosis and adjustment<br />of the bike</h2>
                            <p class="desc">Lorem Ipsum is simply dummy text of<br />the printing and typesetting
                                industry.<br />Lorem Ipsum has been the industry's<br />standard
                                dummy text</p>
                        </div>
                    </li>
                    <li class="services-item">
                        <img src="./images/service-3.png" alt="Service">
                        <div class="text">
                            <h2 class="sub-title">Diagnosis and adjustment<br />of the bike</h2>
                            <p class="desc">Lorem Ipsum is simply dummy text of<br />the printing and typesetting
                                industry.<br />Lorem Ipsum has been the industry's<br />standard
                                dummy text</p>
                        </div>
                    </li>
                    <li class="services-item">
                        <img src="./images/service-4.png" alt="Service">
                        <div class="text">
                            <h2 class="sub-title">Diagnosis and adjustment<br />of the bike</h2>
                            <p class="desc">Lorem Ipsum is simply dummy text of<br />the printing and typesetting
                                industry.<br />Lorem Ipsum has been the industry's<br />standard
                                dummy text</p>
                        </div>
                    </li>
                </ul>
                <a href="#" class="btn">Get discount 10%</a>
            </div>
        </div>
    </section>
    <!-- services end -->

    <!-- about -->
    <section id="about" class="about">
        <div class="container">
            <div class="text">
                <h2 class="title">About Us</h2>
                <p class="desc">We are a big family</p>
            </div>
            <div class="content">
                <div class="left"></div>
                <div class="right">
                    <div class="text">
                        <div class="top">
                            <h2 class="title">Company name</h2>
                            <span>
                        </div>
                        <p class="desc">Lorem Ipsum is simply dummy text of the printing and<br />typesetting industry.
                            Lorem Ipsum has been the<br />industry's standard
                            dummy text ever since the 1500s,<br />when an unknown printer took a galley of type
                            and<br />scrambled it to make a type specimen
                            book. It has<br />survived not only five centuries, but also the leap into<br />electronic
                            typesetting, remaining essentially<br />unchanged. It was popularised in the 1960s with
                            the<br />release of Letraset sheets containing Lorem Ipsum<br />passages, and more
                            recently with desktop publishing<br /> like Aldus PageMaker including versions of<br />Lorem
                            Ipsum.</p>
                    </div>
                    <a href="#" class="btn">Get discount 10%</a>
                </div>
            </div>
        </div>
    </section>
    <!-- about end -->

    <!-- contact -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="content">
                <div class="text">
                    <h2 class="title">Contact Us</h2>
                    <p class="desc">Leave a request</p>
                </div>
                <div class="bottom">
                    <form class="form">
                        <input type="text" title="name" placeholder="Enter your name" required>
                        <input type="email" title="email" placeholder="Enter your email" required>
                        <input type="text" title="email" placeholder="Enter your message" required>
                        <button type="submit">Send</button>
                    </form>
                    <div class="data">
                        <ul class="list">
                            <li class="item">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M20 4H4C2.9 4 2 4.9 2 6V18C2 19.1 2.9 20 4 20H20C21.1 20 22 19.1 22 18V6C22 4.9 21.1 4 20 4ZM19.6 8.25L13.06 12.34C12.41 12.75 11.59 12.75 10.94 12.34L4.4 8.25C4.29973 8.19371 4.21192 8.11766 4.14189 8.02645C4.07186 7.93525 4.02106 7.83078 3.99258 7.71937C3.96409 7.60796 3.9585 7.49194 3.97616 7.37831C3.99381 7.26468 4.03434 7.15581 4.09528 7.0583C4.15623 6.96079 4.23632 6.87666 4.33073 6.811C4.42513 6.74533 4.53187 6.69951 4.6445 6.6763C4.75712 6.65309 4.87328 6.65297 4.98595 6.67595C5.09863 6.69893 5.20546 6.74453 5.3 6.81L12 11L18.7 6.81C18.7945 6.74453 18.9014 6.69893 19.014 6.67595C19.1267 6.65297 19.2429 6.65309 19.3555 6.6763C19.4681 6.69951 19.5749 6.74533 19.6693 6.811C19.7637 6.87666 19.8438 6.96079 19.9047 7.0583C19.9657 7.15581 20.0062 7.26468 20.0238 7.37831C20.0415 7.49194 20.0359 7.60796 20.0074 7.71937C19.9789 7.83078 19.9281 7.93525 19.8581 8.02645C19.7881 8.11766 19.7003 8.19371 19.6 8.25Z"
                                        fill="white" />
                                </svg>
                                <span>test@gmail.com</span>
                            </li>
                            <li class="item">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M19.23 15.26L16.69 14.97C16.3914 14.9349 16.0886 14.968 15.8046 15.0667C15.5206 15.1654 15.2626 15.3273 15.05 15.54L13.21 17.38C10.3712 15.9362 8.06382 13.6288 6.62004 10.79L8.47004 8.94001C8.90004 8.51001 9.11004 7.91001 9.04004 7.30001L8.75004 4.78001C8.69335 4.29219 8.45923 3.84225 8.09228 3.51586C7.72532 3.18947 7.25115 3.00943 6.76004 3.01001H5.03004C3.90004 3.01001 2.96004 3.95001 3.03004 5.08001C3.56004 13.62 10.39 20.44 18.92 20.97C20.05 21.04 20.99 20.1 20.99 18.97V17.24C21 16.23 20.24 15.38 19.23 15.26Z"
                                        fill="white" />
                                </svg>
                                <span>(303) 555-0105</span>
                            </li>
                            <li class="item">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M12 2C8.13 2 5 5.13 5 9C5 13.17 9.42 18.92 11.24 21.11C11.64 21.59 12.37 21.59 12.77 21.11C14.58 18.92 19 13.17 19 9C19 5.13 15.87 2 12 2ZM12 11.5C11.337 11.5 10.7011 11.2366 10.2322 10.7678C9.76339 10.2989 9.5 9.66304 9.5 9C9.5 8.33696 9.76339 7.70107 10.2322 7.23223C10.7011 6.76339 11.337 6.5 12 6.5C12.663 6.5 13.2989 6.76339 13.7678 7.23223C14.2366 7.70107 14.5 8.33696 14.5 9C14.5 9.66304 14.2366 10.2989 13.7678 10.7678C13.2989 11.2366 12.663 11.5 12 11.5Z"
                                        fill="white" />
                                </svg>
                                <span>2715 Ash Dr. San Jose, South Dakota 83475</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- contact end -->

    <!-- footer -->
    <footer style="width: 100%;height: 92px;background: #C4C4C4;"></footer>
    <!-- footer end -->
</body>

</html>
