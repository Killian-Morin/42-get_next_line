
<a name="readme-top"></a>

<!-- PROJECT SUMMARY -->
<div align="center">

  <h3 align="center">get_next_line</h3>

  <p align="center">
    Summary:
    This project is about programming a function that returns a line read from a file descriptor.
  </p>
  <br>
</div>

<!-- TABLE OF CONTENTS -->

- [About The Project](#about-the-project)
- [Sources](#sources)

<!-- ABOUT THE PROJECT -->
## About The Project

This project will not only allow you to add a very convenient function to your collection and it made me discover about static variables in programming.

This is all coded in C.

If you want to run this project, you first have to decomment the `main()` that I put in the get_next_line.c and get_next_line_bonus.c files.

To run the code without the bonus:
```sh
  gcc -Wall -Werror -Wextra get_next_line.c get_next_line_utils.c && ./a.out
```
If you want to change the `BUFFER_SIZE` without modifiying the get_next_line.h file, you can compile the code with following flag: `-D BUFFER_SIZE=n` with `n` as the buffer size that will be used.
When this variable is not set at the compilation it takes the default one: 10.

To compile with the bonus:
```sh
  gcc -Wall -Werror -Wextra get_next_line_bonus.c get_next_line_utils_bonus.c && ./a.out
```
The same process can be done to update the `BUFFER_SIZE`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SOURCES -->
## Sources

* https://www.geeksforgeeks.org/static-variables-in-c/
* https://www.geeksforgeeks.org/input-output-system-calls-c-create-open-close-read-write/

<p align="right">(<a href="#readme-top">back to top</a>)</p>
