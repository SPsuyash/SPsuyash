- 👋 Hi, I’m @SPsuyash
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


      <svg
        width="300"
        height="165"
        viewBox="0 0 300 165"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #e2e9ec;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #e5289e;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #e5289e;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#2b213a"
          stroke-opacity="0"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Most Used Languages</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
      <mask id="rect-mask">
          <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
        </mask>
        
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="177.49"
          height="8"
          fill="#A97BFF"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="177.49"
          y="0"
          width="18.68"
          height="8"
          fill="#b07219"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="196.17000000000002"
          y="0"
          width="17.49"
          height="8"
          fill="#e34c26"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="213.66000000000003"
          y="0"
          width="16.45"
          height="8"
          fill="#3178c6"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="230.11"
          y="0"
          width="10.02"
          height="8"
          fill="#00B4AB"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="240.13000000000002"
          y="0"
          width="19.869999999999997"
          height="8"
          fill="#f34b7d"
        />
      
      
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#A97BFF" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Kotlin 71.00%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#b07219" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Java 7.47%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#e34c26" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        HTML 6.99%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#3178c6" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        TypeScript 6.58%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#00B4AB" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Dart 4.01%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#f34b7d" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C++ 3.95%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
<!---
SPsuyash/SPsuyash is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
