# USART-string

<p align="justify">A program for sending a string of characters received over USART.</p>

<p align="justify">Receiving or sending a string over USART involves reading or writing each character of the string consecutively from or to the UDR register. In this code, each character of a string received over USART is transmitted by the microcontroller directly to another device connected to its TX pin. For seperate devices this could mean that transmission rates would have to be matched to avoid any errors from occuring.</p>

<p align="justify">For more information on USART check out my USART-char repo <a href="https://github.com/asitha-navaratne/USART-char">here</a>.</p>
