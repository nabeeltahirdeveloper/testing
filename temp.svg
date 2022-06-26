<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
				@font-face {
                font-family: "Digital-7";
                font-style: normal;
                font-weight: 400;
                src: local("Digital-7"), local("Digital-7-Regular"),
                    url(https://allfont.net/cache/fonts/digital-7_b73ef91485431ac0271f24009e14ccee.woff)
                    format("woff"),
                    url(https://allfont.net/cache/fonts/digital-7_b73ef91485431ac0271f24009e14ccee.ttf)
                    format("truetype");
                }

                :root {
                --clock-size: 300px;
                }

                * {
                box-sizing: border-box;
                }

                body {
                margin: 0;
                background: #0a0a1d;
                }

                .section {
                height: 100vh;
                width: 100vw;
                display: flex;
                justify-content: flex-start;
                align-items: flex-start;
                flex-direction: column;
                
                }

                .clock-container {
                position: relative;
                width: var(--clock-size);
                height: var(--clock-size);
                display: flex;
                align-items: center;
                justify-content: center;
                }

                .clock-body {
                width: 100%;
                height: 100%;
                border-radius: 50%;
                display: flex;
                justify-content: center;
                align-items: center;
                transform: rotate(180deg);
                animation: move 30s ease infinite;
                }

                .clock-body > .hand > span {
                width: 2px;
                height: calc((var(--clock-size) / 2) - 40px);
                position: absolute;
                border-radius: 10px;
                }

                .clock-body > .minute.hand > span {
                height: calc((var(--clock-size) / 2) - 60px);
                width: 4px;
                margin: -1px;
                }

                .hand > span {
                background: rgb(0, 0, 0);
                }

                .clock-body > .hour.hand > span {
                height: calc((var(--clock-size) / 2) - 80px);
                width: 7px;
                margin: -3px;
                }

                .clock-body .dot {
                position: absolute;
                height: 20px;
                width: 20px;
                border-radius: 50%;
                background: #333;
                animation: move 30s ease infinite;
                border-width: 3px !important;
                }

                .digital-time > span {
                font-size: 6rem;
                }

                .digital-time {
                font-family: "Digital-7", arial !important;
                display: flex;
                align-items: center;
                font-size: 3rem;
                width: 300px;
                }

                .digital-time > h2,
                .digital-time > span {
                animation: move 30s ease infinite;
                background: none !important;
                border: none !important;
                box-shadow: none !important;
                }

                .num {
                position: absolute;
                color: #000;
                font-family: "digital-7", arial;
                font-size: 2rem;
                z-index: 9;
                }
                .n-12 {
                top: 20px;
                }

                .n-3 {
                right: 20px;
                }
                .n-6 {
                bottom: 20px;
                }

                .n-9 {
                left: 20px;
                }

                @keyframes move {
                0% {
                    border: 8px solid #3bffde;
                    box-shadow: 0 0 15px 10px rgba(61, 255, 223, 0.788);
                    background: #c6fff5;
                    color: #c6fff5;
                }
                25% {
                    border: 8px solid rgb(255, 0, 76);
                    box-shadow: 0 0 15px 10px rgba(255, 0, 76, 0.76);
                    background: rgb(255, 176, 200);
                    color: rgb(255, 176, 200);
                }
                50% {
                    border: 8px solid rgb(255, 0, 255);
                    box-shadow: 0 0 15px 10px rgba(255, 0, 255, 0.671);
                    background: rgb(255, 200, 217);
                    color: rgb(255, 200, 217);
                }
                75% {
                    border: 8px solid rgb(111, 0, 255);
                    box-shadow: 0 0 15px 10px rgba(111, 0, 255, 0.644);
                    background: rgb(209, 174, 255);
                    color: rgb(209, 174, 255);
                }
                100% {
                    border: 8px solid #3bffde;
                    box-shadow: 0 0 15px 10px rgba(59, 255, 222, 0.733);
                    background: #c6fff5;
                    color: #c6fff5;
                }
                }

			</style>
             <div class="main-container">
			 <div class="section">
      <div class="clock-container">
        <span class="num n-12">12</span>
        <span class="num n-3">3</span>
        <span class="num n-6">6</span>
        <span class="num n-9">9</span>
        <div class="clock-body">
          <div class="hour hand" id="hour">
            <span></span>
          </div>
          <div class="minute hand" id="minute">
            <span></span>
          </div>
          <div class="second hand" id="second">
            <span></span>
          </div>
          <div class="dot"></div>
        </div>
      </div>
      <div class="digital-time">
        <h2 id="digital-hour"></h2>
        <h2>:</h2>
        <h2 id="digital-minute"></h2>
        <h2>:</h2>
        <h2 id="digital-second"></h2>
      </div>
    </div>
    </div>
		</div>
	</foreignObject>
        <script xlink:href="main.js" />

</svg>
