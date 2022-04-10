* {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: "Bree Serif", sans-serif;
}

body {
    overflow: hidden;
}

#sidebar {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 200px;
    height: 100vh;
    background: #00ff0d;
    text-align: center;
    transform-origin: left;
    transform: perspective(1200px) rotateY(90deg);
    transition: all 400ms ease;
}

#sidebar ul li {
    color: #ccc;
    font-size: 20px;
    width: 100%;
    height: 50px;
    border-bottom: 1px solid #222222;
    line-height: 50px;
}

#sidebar.active {
    transform: perspective(1200px) rotateY(0deg);
}

#toggle-btn {
    position: absolute;
    left: 30px;
    top: 20px;
    transition: left 200ms linear 0ms, transform 300ms ease 100ms;
}

#toggle-btn.active {
    left: 230px;
    transform: rotate(360deg);
}

#toggle-btn span {
    position: relative;
    top: 0px;
    display: block;
    background: #1a1a1a;
    width: 30px;
    height: 5px;
    margin: 5px 0px;
    cursor: pointer;
    transition: transform 300ms ease 200ms;
}

#toggle-btn.active span:nth-child(1) {
    top: 10px;
    transform: rotate(45deg);
}

#toggle-btn.active span:nth-child(2) {
    opacity: 0;
}

#toggle-btn.active span:nth-child(3) {
    top: -10px;
    transform: rotate(-45deg);
}

body {
    font-family: 'Open Sans', sans-serif;
    background-color: #F3F5F6;
    padding-left: 100px;
    padding-right: 100px;
}

.header-image {
    width: 100%;
    height: 400px;
    object-fit: cover;
    object-position: 50% 15%;
    display: block;
}

.headline {
    color: #831D17;
    flex: 1;
}

.image-container {
    background-color: white;
    padding: 16px;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

a {
    color: #831D17;
    text-decoration: none;
    margin-left: 16px;
    font-weight: 700;
}

a:hover {
    text-decoration: underline;
}

.text-highlight {
    color: #484846;
    font-size: 47px;
}

.text-container {
    background-color: #DEDEDE;
    padding: 8px;
    color: #484846;
    font-weight: 600;
}

.maps-container {
    margin-top: 16px;
    display: flex;
    justify-content: space-between;
}

.maps-right {
    margin-left: 16px;
    width: 30%;
}

.maps-frame {
    border: 0;
    height: 350px;
    width: 70%;
}

.legal-content {
    padding: 8px;
}

.legal-text {
    margin-right: 16px;
}

@media (max-width: 800px) {
    .flex {
        flex-direction: column;
    }
}
