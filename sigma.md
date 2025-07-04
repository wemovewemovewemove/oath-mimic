<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Authorize access - Roblox</title>
  <link rel="icon" href="/assets/favicon.ico" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Helvetica:wght@400;800&display=swap" />
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Builder Sans", Helvetica, Arial, sans-serif;
      background-color: rgb(17, 18, 22);
      color: white;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 2rem 1rem;
      flex: 1;
    }

    header, footer {
      width: 100%;
    }

    header img {
      display: block;
    }

    .logo-bar {
      padding: 1rem 2rem;
    }

    .title {
      font-size: 24px;
      font-weight: 800;
      margin-bottom: 1rem;
    }

    .divider {
      border: none;
      border-top: 1px solid #444;
      margin: 1rem 0;
    }

    .account-box {
      margin-top: 1rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin: 12px 0;
    }

    .username {
      font-weight: bold;
      font-size: 18px;
      margin-bottom: 1rem;
    }

    .MuiButtonBase-root {
      display: inline-flex;
      -webkit-box-align: center;
      align-items: center;
      -webkit-box-pack: center;
      justify-content: center;
      position: relative;
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
      cursor: pointer;
      user-select: none;
      vertical-align: middle;
      appearance: none;
      min-width: 64px;
      background-color: rgb(229, 229, 230);
      width: 100%;
      font-family: "Builder Sans", Helvetica, Arial, sans-serif;
      font-weight: 800;
      font-style: normal;
      font-size: 16px;
      line-height: 100%;
      text-transform: none;
      box-shadow: none;
      color: rgb(17, 18, 22);
      outline: 0px;
      border: 0;
      text-decoration: none;
      transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1), 
                  box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1), 
                  border-color 250ms cubic-bezier(0.4, 0, 0.2, 1), 
                  color 250ms cubic-bezier(0.4, 0, 0.2, 1);
      border-radius: 8px;
      padding: 10px 16px;
      margin: 24px 0px;
    }

    .divider-or {
      display: flex;
      align-items: center;
      text-align: center;
      color: #999;
      margin: 1rem 0;
    }

    .divider-or::before,
    .divider-or::after {
      content: "";
      flex: 1;
      border-bottom: 1px solid #444;
    }

    .divider-or:not(:empty)::before {
      margin-right: .75em;
    }

    .divider-or:not(:empty)::after {
      margin-left: .75em;
    }

    footer {
      padding: 2rem;
      background-color: rgb(17, 18, 22);
    }

    .footer-container {
      max-width: 960px;
      margin: 0 auto;
    }

    .MuiGrid-root {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
    }

    .MuiGrid-container {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      font-size: 13px;
    }

    .MuiGrid-item {
      flex-grow: 1;
    }

    .MuiTypography-root {
      color: #999;
      text-decoration: none;
    }

    .MuiGrid-root img {
      max-width: 124px;
      height: auto;
    }

    .MuiGrid-container.css-1njkcha-Grid-root-copyright {
      font-size: 12px;
      color: #777;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo-bar">
      <img src="https://authorize.roblox.com/assets/logo/global_logo_white.svg" width="195" height="35" alt="logo" />
    </div>
  </header>

  <main class="container">
    <div class="title">Select Account to Continue to Cytosine Verification</div>
    <hr class="divider" />
    <div class="account-box">
      <span>You’re logged in as</span>
      <img class="avatar" src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-95958C2AF5E21A0C93AD09DA0C40A7B1-Png/150/150/AvatarHeadshot/Png/noFilter" alt="DERP5034">
      <div class="username">thuggernaut</div>
      <button class="MuiButtonBase-root" type="button">Continue<span class="MuiTouchRipple-root css-w0pj6f"></span></button>
      <div class="divider-or">or</div>
      <button class="MuiButtonBase-root" type="button">Change Account<span class="MuiTouchRipple-root css-w0pj6f"></span></button>
    </div>
  </main>

  <footer>
    <div class="footer-container">
      <div class="MuiGrid-root MuiGrid-container">
        <div class="MuiGrid-root MuiGrid-item MuiGrid-grid-sm-12 MuiGrid-grid-md-auto css-1o1b8p-Grid-root-logo">
          <img src="https://authorize.roblox.com/assets/logo/global_logo_white.svg" alt="logo" width="124" height="21.52">
        </div>
        <div class="MuiGrid-root MuiGrid-item MuiGrid-grid-xs-12 MuiGrid-grid-sm-12 css-12jpqt6-Grid-root">
          <div class="MuiGrid-root MuiGrid-container MuiGrid-item css-1e5a888-Grid-root-externalLinks">
            <a class="MuiTypography-root MuiTypography-inherit MuiLink-root MuiLink-underlineHover css-gjcsa4-Link-colorPrimary-Link-root" href="https://corp.roblox.com/" target="_blank"><span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">About Us</span></a>
            <span class="css-rtgaaj-linkDivider">|</span>
            <a class="MuiTypography-root MuiTypography-inherit MuiLink-root MuiLink-underlineHover css-gjcsa4-Link-colorPrimary-Link-root" href="https://corp.roblox.com/careers/" target="_blank"><span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">Join Us</span></a>
            <span class="css-rtgaaj-linkDivider">|</span>
            <a class="MuiTypography-root MuiTypography-inherit MuiLink-root MuiLink-underlineHover css-gjcsa4-Link-colorPrimary-Link-root" href="https://en.help.roblox.com/hc/en-us/articles/115004647846-Roblox-Terms-of-Use" target="_blank"><span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">Terms</span></a>
            <span class="css-rtgaaj-linkDivider">|</span>
            <a class="MuiTypography-root MuiTypography-inherit MuiLink-root MuiLink-underlineHover css-gjcsa4-Link-colorPrimary-Link-root" href="https://en.help.roblox.com/hc/en-us/articles/115004630823-Roblox-Privacy-and-Cookie-Policy-" target="_blank"><span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">Privacy</span></a>
            <span class="css-rtgaaj-linkDivider">|</span>
            <a class="MuiTypography-root MuiTypography-inherit MuiLink-root MuiLink-underlineHover css-gjcsa4-Link-colorPrimary-Link-root" href="https://www.roblox.com/info/accessibility" target="_blank"><span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">Accessibility</span></a>
          </div>
          <div class="MuiGrid-root MuiGrid-container MuiGrid-item css-1njkcha-Grid-root-copyright">
            <span class="MuiTypography-root MuiTypography-inherit css-zl9cle-Typography-root-Typography-body2-Typography-colorSecondary">©2025 Roblox Corporation. Roblox, the Roblox logo and Powering Imagination are among our registered and unregistered trademarks in the U.S. and other countries.</span>
          </div>
        </div>
      </div>
    </div>
  </footer>
</body>
</html>
