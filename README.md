<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        @keyframes gradient {
          0% {
            background-position: 0% 50%;
          }
          50% {
            background-position: 100% 50%;
          }
          100% {
            background-position: 0% 50%;
          }
        }

        .icon-grid {
          display: flex;
          flex-wrap: wrap;
          gap: 10px;
        }
      
        .icon-cell {
          background-color: white;
          box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
          width: 100px;
          height: 100px;
          display: flex;
          justify-content: center;
          align-items: center;
        }
      
        .icon-cell img {
          max-width: 80%;
          max-height: 80%;
        }

        .container {
          background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
          background-size: 400% 400%;
          animation: gradient 15s ease infinite;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .container {
            animation: none;
          }

          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        Soy Diego, <strong>Desarrollador Full Stack</strong>. Algunas de las tecnologías con las que trabajo:
      </div>
      <div class="icon-grid">
        <div class="icon-cell">
          <img height="32" width="32" src="https://cdn.simpleicons.org/angular/d6002f" alt="Icon 1"/>
        </div>
        <div class="icon-cell">
          <img height="32" width="32" src="https://cdn.simpleicons.org/react/5ed3f3" alt="Icon 2"/>
        </div>
        <div class="icon-cell">
          <img height="32" width="32" src="https://cdn.simpleicons.org/typescript/2f74c0" alt="Icon 3"/>
        </div>
        <div class="icon-cell">
          <img height="32" width="32" src="https://cdn.simpleicons.org/nodedotjs/88c249" alt="Icon 4"/>
        </div>
        <div class="icon-cell">
          <img height="32" width="32" src="https://cdn.simpleicons.org/express" alt="Icon 5"/>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

![DiegoPertierraM's GitHub stats](https://github-readme-stats.vercel.app/api?username=DiegoPertierraM&show_icons=true&theme=buefy)
