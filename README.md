import { useEffect } from 'react';

export default function Home() {
  useEffect(() => {
    // Esto será para agregar un poco de animación simple si lo deseas.
    const typewriter = document.querySelector('.typewriter');
    if (typewriter) {
      typewriter.classList.add('animate-typewriter');
    }
  }, []);

  return (
    <div className="home-container">
      <section id="about" className="hero-section">
        <div className="hero-container">
          <div className="image-container">
            <img src="assets/imgs/people.png" alt="Leonel Arízaga" className="hero-image" />
          </div>
          <div className="text-container">
            <h1 className="name">Leonel Arízaga Díaz</h1>
            <h2 className="title">Programador Full Stack Web &amp; App Developer</h2>
            <p className="description">
              Soy un desarrollador con experiencia en tecnologías como NodeJS, React, Angular, y Laravel. Me apasiona crear soluciones web innovadoras y robustas.
            </p>
            <div className="skills">
              <p className="skill">NodeJS</p>
              <p className="skill">React</p>
              <p className="skill">Angular</p>
              <p className="skill">Laravel</p>
            </div>
          </div>
        </div>
      </section>

      <style jsx>{`
        /* Estilos generales */
        * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: 'Arial', sans-serif;
        }

        body {
          background-color: #f4f4f4;
          font-size: 16px;
          line-height: 1.6;
          color: #333;
        }

        /* Sección principal */
        .hero-section {
          display: flex;
          justify-content: center;
          align-items: center;
          min-height: 100vh;
          background: linear-gradient(135deg, #ff7e5f, #feb47b);
          padding: 20px;
        }

        /* Contenedor del contenido */
        .hero-container {
          display: flex;
          align-items: center;
          max-width: 1200px;
          width: 100%;
          background-color: white;
          border-radius: 10px;
          overflow: hidden;
          box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        /* Imagen */
        .image-container {
          flex: 1;
          text-align: center;
          padding: 20px;
        }

        .hero-image {
          width: 100%;
          max-width: 300px;
          border-radius: 50%;
          object-fit: cover;
          box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* Contenedor de texto */
        .text-container {
          flex: 2;
          padding: 40px;
        }

        .name {
          font-size: 2rem;
          font-weight: bold;
          color: #333;
          margin-bottom: 10px;
          text-align: center;
        }

        .title {
          font-size: 1.5rem;
          font-weight: 500;
          color: #555;
          margin-bottom: 20px;
          text-align: center;
        }

        .description {
          font-size: 1rem;
          color: #666;
          line-height: 1.5;
          margin-bottom: 30px;
          text-align: center;
        }

        .skills {
          display: flex;
          justify-content: center;
          gap: 15px;
        }

        .skill {
          font-size: 1rem;
          font-weight: 600;
          color: #fff;
          background-color: #333;
          padding: 8px 15px;
          border-radius: 30px;
          text-transform: capitalize;
          transition: background-color 0.3s ease;
        }

        .skill:hover {
          background-color: #feb47b;
        }

        /* Animación de tipo escritor */
        .animate-typewriter {
          animation: typewriter 4s steps(40) 1s forwards;
          white-space: nowrap;
          overflow: hidden;
        }

        /* Efecto de escritura */
        @keyframes typewriter {
          from {
            width: 0;
          }
          to {
            width: 100%;
          }
        }
      `}</style>
    </div>
  );
}
