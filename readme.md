
<main>
<article>
<h2> Meta Commands </h2>
Meta commands in psql are commands that are prefixed with a backslash (\). They are used to control the behavior of psql, rather than to manipulate data in the database.
  <ul>
    <li>\c - Connect to a database.</li>
    <li>\d - Display the schema for a table.</li>
    <li>\e - opens the most recently entered command in the default text editor.</li>
    <li>\h - Display help information</li>
    <li>\l - List all databases</li>
    <li>\q - Quit without saving changes</li>
    <li>\r - Reload the current database</li>
  </ul>
  You can find a list of all meta commands by typing \? at the psql prompt.
</article>

<article>
  <h2> SQL Commands</h2>
  SQL commands are used to manipulate data in the database. They are the same commands that you would use in a regular SQL client
  <ul>
    <li>SELECT: Retrieve data from a table</li>
    <li>INSERT: Insert data into a table</li>
    <li>UPDATE: Update data in a table</li>
    <li>DELETE: Delete data from a table</li>
  </ul>
</article>
</main>