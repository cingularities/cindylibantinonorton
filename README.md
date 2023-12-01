<!-- =^..^= Created by JZimz. Learn more at jzimz.com -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>Gamertag</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;900&display=swap" rel="stylesheet">
    <style>
      body {
        font-family: 'Roboto Slab', serif;
        font-weight: 300;
        color: #0d0f11;
      }
      strong {
        font-weight: 600;
      }

      #page-home {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 60px;
      }

      .profile-photo {
        width: 130px;
        height: 130px;
        background-color: white;
        border-radius: 50%;
        background-repeat: no-repeat;
        background-image: url('assets/profile.jpeg');
        background-size: 118%;
        background-position: 70% 28%
      }
      .profile-photo:hover {
        background-image: url('assets/profile-alt.png');
        background-size: 100%;
      }

      .profile-text h1 {
        font-family: 'Roboto', sans-serif;
        font-weight: 900;
        margin-top: 0.5em;
        font-size: 2em;
        text-align: center;
      }

      .page-body {
        padding: 0 20px;
        max-width: 520px;
      }

      .linkage {
        font-family: 'Roboto', sans-serif;
        margin-top: 40px;
        text-align: center;
        display: flex;
        justify-content: space-evenly;
      }

      .linkage .link-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-decoration: none;
        font-weight: 400;
        color: #0d0f11;
      }

      .linkage .icon {
        height: 90px;
        width: 90px;
        border-radius: 50%;
        margin-bottom: 10px;
        background-color: #0d0f11;
      }

      @media screen and (max-width: 400px) {
        .linkage .icon {
          height: 64px;
          width: 64px;
        }
      }

    </style>
  </head>
  <body>
    <div id="app">
      <div id="page-home">
        <div class="profile-photo"></div>
        <div class="profile-text">
          <h1>Your Name</h1>
        </div>
        <div class="page-body">
          <div class="about">
            <strong>Lorem Ipsum</strong> is simply dummy text of the printing
            and typesetting industry. Lorem Ipsum has been the industry's
            standard dummy text ever since the 1500s, when an unknown printer
            took a galley of type and scrambled it to make a type specimen book.
            It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged. It was
            popularised in the 1960s with the release of Letraset sheets
            containing Lorem Ipsum passages, and more recently with desktop
            publishing software like Aldus PageMaker including versions of
            Lorem Ipsum.
          </div>
          <div class="linkage">
            <a href="https://www.twitch.tv/jzimz" class="link-item twitch">
              <div class="icon"></div>
              <div class="label">Twitch</div>
            </a>
            <a href="https://discord.gg/aV37twc" class="link-item discord">
              <div class="icon"></div>
              <div class="label">Discord</div>
            </a>
            <a href="https://www.instagram.com/jzimz.tv/"
              class="link-item instagram">
              <div class="icon"></div>
              <div class="label">Instagram</div>
            </a>
            <a href="https://twitter.com/jzimztv" class="link-item twitter">
              <div class="icon"></div>
              <div class="label">Twitter</div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
