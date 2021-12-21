
      <svg
        width="300"
        height="85"
        viewBox="0 0 300 85"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #70a5fd;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          .lang-name { font: 400 11px 'Segoe UI', Ubuntu, Sans-Serif; fill: #38bdae }

          
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
  
          * { animation-duration: 0s !important; animation-delay: 0s !important; }
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#1a1b27"
          stroke-opacity="1"
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
      
    </svg>
  
        </g>
      </svg>
    
