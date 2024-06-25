<h2 align="left">
  Crear un ETL y entender todo el proceso de extracción desde una base de datos transaccional OLTP y otras fuentes de datos como archivos CSV y JSON.<br>
  Transformar y limpiar los datos, y cargarlos en bases de datos en la nube especializadas para analítica de tipo OLAP.
</h2>

<h3>Creación de la Base de Datos con Docker</h3>
<p>Para crear una instancia de PostgreSQL utilizando Docker, ejecuta el siguiente comando:</p>
<pre>
<code>
sudo docker run -d --name=postgres -p 5432:5432 -v postgres-volume:/var/lib/postgresql/data -e POSTGRES_PASSWORD=mysecretpass postgres
</code>
</pre>

<h3>Configuración de la Conexión en DataSpell</h3>
<p>Introduce los siguientes datos para la conexión en DataSpell:</p>
<ul>
  <li><strong>Name:</strong> local_postgres</li>
  <li><strong>Host:</strong> localhost</li>
  <li><strong>Port:</strong> 5432</li>
  <li><strong>User:</strong> postgres</li>
  <li><strong>Database:</strong> postgres</li>
  <li><strong>URL (opcional):</strong> jdbc:postgresql://localhost:5432/postgres</li>
  <li><strong>Password:</strong> mysecretpass</li>
</ul>

<h3>Objetivos</h3>
<ol>
  <li>Dominar conceptos ETL.</li>
  <li>Manejo de Python para ETL.</li>
  <li>Uso eficiente de Python.</li>
  <li>Integración de herramientas.</li>
</ol>

<h3>Software y Herramientas</h3>
<ul>
  <li>Docker.</li>
  <li>Git.</li>
  <li>Python 3.</li>
  <li>Pandas.</li>
  <li>DataSpell.</li>
  <li>Pip.</li>
  <li>Cuenta de AWS.</li>
  <li>PostgreSQL.</li>
  <li>Anaconda.</li>
</ul>


<pre>
<code>
# Crear contenedor de PostgreSQL con Docker
sudo docker run -d --name=postgres -p 5432:5432 -v postgres-volume:/var/lib/postgresql/data -e POSTGRES_PASSWORD=mysecretpass postgres
</code>
</pre>

</body>
</html>
