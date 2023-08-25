<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=, initial-scale=1.0" />
    <title>Raijin Website</title>
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap");

      body {
        background-image: url(https://images2.alphacoders.com/115/1152188.jpg);
        background-size: auto auto;
        background-repeat: no-repeat;
        color: #fff;
        background-color: rgb(31, 31, 29);
        text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000,
          1px 1px 0 #000;
      }
      .header {
        text-align: center;
        margin-top: 50px;
        margin-bottom: 120px;
        font-family: "Rajdhani", sans-serif;
      }

      .socials {
        text-align: center;
        margin-bottom: 120px;
        font-family: "Nunito", sans-serif;
      }

      .link {
        margin-top: 150px;
        color: white;
      }

      .system {
        margin: auto;
        width: 640px;
        text-align: center;
        font-family: "Nunito", sans-serif;
      }

      html,
      body {
        height: 200px;
      }

      .wrap {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .button {
        min-width: 200px;
        min-height: 60px;
        font-family: "Nunito", sans-serif;
        font-size: 22px;
        text-transform: uppercase;
        letter-spacing: 1.3px;
        font-weight: 700;
        color: white;
        background-color: white;
        text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000,
          1px 1px 0 #000;
        background: #4fd1c5;
        background: linear-gradient(
          90deg,
          rgba(129, 230, 217, 1) 0%,
          rgba(79, 209, 197, 1) 100%
        );
        border: none;
        border-radius: 1000px;
        box-shadow: 12px 12px 24px rgba(79, 209, 197, 0.64);
        transition: all 0.3s ease-in-out 0s;
        cursor: pointer;
        outline: none;
        position: relative;
        padding: 10px;
      }

      button::before {
        content: "";
        border-radius: 1000px;
        min-width: calc(200px + 12px);
        min-height: calc(60px + 12px);
        border: 6px solid #00ffcb;
        box-shadow: 0 0 60px rgba(0, 255, 203, 0.64);
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        opacity: 0;
        transition: all 0.3s ease-in-out 0s;
      }

      .button:hover,
      .button:focus {
        color: #fff;
        transform: translateY(-6px);
      }

      button:hover::before,
      button:focus::before {
        opacity: 1;
      }

      button::after {
        content: "";
        width: 30px;
        height: 30px;
        border-radius: 100%;
        border: 6px solid #00ffcb;
        position: absolute;
        z-index: -1;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        animation: ring 1.5s infinite;
      }

      button:hover::after,
      button:focus::after {
        animation: none;
        display: none;
      }

      @keyframes ring {
        0% {
          width: 15px;
          height: 15px;
          opacity: 1;
        }
        100% {
          width: 150px;
          height: 150px;
          opacity: 0;
        }
      }
      .center {
        margin: 0 auto;
        width: 750px;
        display: block;
        border-radius: 15px;
      }
    </style>
  </head>
  <body>
    <div class="header">
      <h1>Raijin</h1>
      <h2>Neo Strafe</h2>
    </div>
    <div class="socials">
      <h3>Watch me here</h3>
      <a
        class="link"
        href="https://www.tiktok.com/@raijinapex?is_from_webapp=1&sender_device=pc"
        >TIKTOK</a
      >
    </div>
    <div class="system">
      <h3>How does it work</h3>
      <p>
        The strafe script is simple to use. After the download, start the ".exe"
        and bind your activation key. It works both with keyboard and mouse as
        well as with controller. You can change input type in the settings.
        After you're done with the setting, just start Apex Legends and ingame
        just press youre activaton key and you're good to go.
      </p>
    </div>
    <div class="wrap">
      <a
        href="https://www.mediafire.com/file/m3eslqra02qdpyy/RaijinNeoStrafeBinder.exe/file
      "
        download
        ><button class="button">Download</button></a
      >
    </div>
    <div class="system">
      <h3>Comman Issues</h3>
      <p>
        The programm could be detected by an anti-cheat because it has to take
        your keyinputs from windows so it can change it to the right ones. On
        controller it obviously needs the stick inputs.
      </p>
    </div>
  </body>
</html>
