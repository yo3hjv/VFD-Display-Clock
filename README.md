# VFD-Display-Clock
A nice desktop clock from a POS VFD CD-7220 
You can see it in action here: https://www.youtube.com/watch?v=q2pe_60TFq0&ab_channel=YO3HJV

/*
 * VFD Clock rev final release
 * Dec. 2020
 *      Month with name
 *      Date, UTC time, Local time
 *      UTC offset
 * 
 * Author: YO3HJV, Adrian
 * LICENSE: If you like it and use it, please send me an e-mail
 * at: yo3hjv@gmail.com with a nice picture from your QTH or surroundings.
 * 
 * The time is set with the help of the PC, therefore
 * we will define UTC as a result of the Local time + or -
 * offset.
 * This will affect the date changing; the date will change 
 * according to Local time.
 *   HW: DS1307 on I2C
 *       VFD TTL UART input connect to Tx port defined on mySerial
 */
