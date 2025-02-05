<div style="font-family: Arial, sans-serif; line-height: 1.6; background-color: #f4f4f4; padding: 20px;">
  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 20px;">
    <h1 style="color: #4CAF50;">🌍 Modelo Matemático del Dengue en Santa Cruz, Bolivia</h1>
    <p>
      Este proyecto utiliza <span style="color: #FF5733; font-weight: bold;">ecuaciones diferenciales</span> para modelar la propagación del dengue en Santa Cruz, Bolivia. 
      Usamos un <span style="color: #FF5733; font-weight: bold;">modelo logístico</span> basado en datos reales para prever la expansión de la enfermedad.
    </p>
  </div>

  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 20px;">
    <h2 style="color: #4CAF50;">🔬 ¿Qué estamos haciendo?</h2>
    <ul>
      <li>Aplicamos un modelo logístico para simular el comportamiento de la propagación del dengue.</li>
      <li>Usamos datos reales del Ministerio de Salud para validar el modelo.</li>
      <li>Desarrollamos una solución matemática que describe la dinámica de la población infectada utilizando ecuaciones diferenciales.</li>
    </ul>
  </div>

  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 20px;">
    <h2 style="color: #4CAF50;">💻 ¿Cómo lo implementamos?</h2>
    <p>
      Utilizamos <span style="color: #FF5733; font-weight: bold;">programación matemática</span> para resolver la ecuación diferencial de variables separables, como se muestra en el siguiente ejemplo:
    </p>
    <pre style="background-color: #f5f5f5; padding: 10px; border-radius: 4px; font-size: 1.1em; font-family: Consolas, monospace; margin: 10px 0;">
dN/dt = k * (M - N) * N / M
    </pre>
    <p>En donde:</p>
    <ul>
      <li><strong>N</strong>: población infectada</li>
      <li><strong>M</strong>: población total</li>
      <li><strong>k</strong>: constante de tasa de infección</li>
    </ul>
  </div>

  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 20px;">
    <h2 style="color: #4CAF50;">📊 Resultados</h2>
    <p>
      El modelo nos permitió estimar que, partiendo de 712 casos confirmados, después de una semana hay 2012 personas infectadas. A continuación, se muestran los resultados de la simulación:
    </p>
    <table style="width:100%; border-collapse: collapse; margin-top: 10px;" border="1">
      <tr>
        <th style="padding:10px; text-align:center;">Tiempo (semanas)</th>
        <th style="padding:10px; text-align:center;">Infectados (N)</th>
      </tr>
      <tr>
        <td style="padding:10px; text-align:center;">0</td>
        <td style="padding:10px; text-align:center;">712</td>
      </tr>
      <tr>
        <td style="padding:10px; text-align:center;">1</td>
        <td style="padding:10px; text-align:center;">2012</td>
      </tr>
      <tr>
        <td style="padding:10px; text-align:center;">2</td>
        <td style="padding:10px; text-align:center;">5680</td>
      </tr>
      <tr>
        <td style="padding:10px; text-align:center;">3</td>
        <td style="padding:10px; text-align:center;">16003</td>
      </tr>
      <tr>
        <td style="padding:10px; text-align:center;">4</td>
        <td style="padding:10px; text-align:center;">44844</td>
      </tr>
    </table>
  </div>

  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 20px;">
    <p>Para más detalles sobre el código, la formulación matemática y los resultados, descarga el PDF completo del proyecto:</p>
    <p>
  <a href="EcuacionesDiferencialesDengue.pdf" 
     style="
       display: inline-block;
       background: linear-gradient(45deg, #4CAF50, #45a049);
       color: white;
       padding: 12px 25px;
       border-radius: 6px;
       text-decoration: none;
       font-size: 1.2em;
       box-shadow: 0 4px 8px rgba(0,0,0,0.2);
       transition: transform 0.2s, box-shadow 0.2s;
     "
     onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.3)';" 
     onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 4px 8px rgba(0,0,0,0.2)';"
     download>
     Descargar PDF
  </a>
</p>
  </div>

  <div style="background-color: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
    <h2 style="color: #4CAF50;">🔍 Conclusión</h2>
    <p>
      Gracias a las ecuaciones diferenciales y los métodos matemáticos, demostramos cómo el dengue podría expandirse rápidamente en Santa Cruz si no se toman medidas adecuadas. 
      El modelo predice un crecimiento exponencial, lo que subraya la importancia de actuar rápidamente para controlar la epidemia.
    </p>
    <p>
      Este proyecto es solo una aproximación, y no considera factores como el clima o las medidas de control, lo que podría mejorar la precisión del modelo.
    </p>
  </div>
</div>
