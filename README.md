<h1>get_next_line <a href="https://github.com/JaeSeoKim/badge42"><img src="https://badge42.vercel.app/api/v2/cl8uf09z900060gl2pg6sdczb/project/2411891" alt="samoreno's 42 get_next_line Score" /></a></h1>
<h2>Project description</h2>
<div>
<!--  <a href="https://github.com/JaeSeoKim/badge42">
    <img align="center" src="https://badge42.herokuapp.com/api/project/samoreno/ft_printf"/>
  </a> -->
  <p>This is the third project at 42 Madrid. The aim is to learn about static functions in C. The goal is to create a function that with repeated calls (e.g., using a loop) lets you read the text file pointed to by the file descriptor, one line at a time. The following table shows the requirements:
  <table>
    <tr>
      <th>Function name</th>
      <td>get_next_line</td>
    </tr>
    <tr>
      <th>Prototype</th>
      <td>char *get_next_line(int fd);</td>
    </tr>
    <tr>
      <th>Parameters</th>
      <td>fd: The file descriptor to read from</td>
    </tr>
    <tr>
      <th>Return value </th>
      <td>Read line: correct behavior. NULL: there is nothing else to read, or an error occurred</td>
    </tr>
    <tr>
      <th>External C functions allowed</th>
      <td>read, malloc, free</td>
    </tr>
    <tr>
      <th>Description</th>
      <td>Write a function that returns a line read from a file descriptor</td>
    </tr>
</table>
  </p>
  <p>
  The "trick of this exercice is that the buffer size that the C function read() uses to know how many bytes to attempt to read and thus write in the buffer cannot be chosen. it is given externally by the correctors (in this case a BUFFER_SIZE  = 42 has been provided as a macro in the .h file). Global variables are also forbidden.
  </p>
</div>
