<svelte:head>
    <title>Яшин Никита</title>
</svelte:head>

    <div class="container">
        <div class="info">
            <div class="animate-background">
                <div class="container info-container">
                  <div class="info-text">
                     <h1>
                          <p class="animate-text-1">Lorem, ipsum dolor sit,</p>
                          <p class="text-2">Lorem ipsum dolor sit amet.</p>
                       </h1>
                 </div>
                 <h2 class="subtitle">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit neque.
                     Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet veritatis nisi.
                  </h2>
                  <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
                  <div style="color:black" class="scroll-button animate-scroll" tabindex="0">
                      <a href="/about">Click here</a><div class="arrow">-</div>
                 </div>
               </div>
             </div>
        </div>
    </div>

    <div class="background-div"></div>

    <style>
        .info{
            text-align: center;
            position: relative;
        }

        .info-container {
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: left;
            align-items: start;
        }

        .container {
            max-width: 1400px;
            margin: 190px 0 0 2.5rem;
        }

        .info h1 {
            font-size: 4rem;
            margin: 0;
        }

        .info h1 p{
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
        }

        .info h2 p{
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.50rem;
        }

        .background-div {
            background-color: #ecebe8;
            width: 100%;
            height: 56vh;
            margin: -205px auto;
        }

        .info .info-text {
            position: relative;
        }

        .scroll-button {
            display: flex;
            border: none;
            outline: none;
            cursor: pointer;
        }

        .scroll-button .arrow {
            margin-left: 0.50rem;
        }
    </style>