# OS_practice
8. D = A – 1 - C – 3 + B 구현하고, D를 출력하라.<br>
 * A값 : 1010 (메모리주소 1100)<br>
 * B값 : 0001 (메모리주소 0111)<br>
 * C값 : 0001 (메모리주소 1111)<br>
 * D값 : 0110 (메모리주소 0001)<br>
WRITE A 1100 1010<br>
WRITE B 0111 0001<br>
WRITE C 1111 0001<br>
WRITE D 0001 0110<br>
SUB A 0001<br>
STORE A<br>
SUB A C<br>
STORE A<br>
SUB A 0011<br>
STORE A<br>
ADD A B<br>
STORE D<br>
PRINT D<br>
![Image](https://github.com/user-attachments/assets/7ed93f29-3740-4452-a78a-d67be9758ddc)<br>
![Image](https://github.com/user-attachments/assets/fb95480e-981c-4720-b700-b492d8337ef8)<br>


16. E = A + B - 6 - C – D – 1 구현하고, E를 출력하라.<br>
 * A값 : 1000 (메모리주소 1100)<br>
 * B값 : 0011 (메모리주소 1110)<br>
 * C값 : 0001 (메모리주소 1000)<br>
 * D값 : 0010 (메모리주소 0001)<br>
 * E값 : 1111 (메모리주소 1011)<br>
WRITE A 1100 1000<br>
WRITE B 1110 0011<br>
WRITE C 1000 0001<br>
WRITE D 0001 0010<br>
WRITE E 1011 1111<br>
ADD A B<br>
STORE A<br>
SUB A 0110<br>
STORE A<br>
SUB C D<br>
STORE C<br>
SUB C 0001<br>
STORE C<br>
SUB A C<br>
STORE E<br>
PRINT E<br>
![Image](https://github.com/user-attachments/assets/ba09a5eb-6a4e-4136-912d-1b7e51f074e3)<br>
![Image](https://github.com/user-attachments/assets/26a42518-db35-4229-9e9c-ee130f9bb808)
