//  This is CodingCoffee for C/C++ DBus gitpod example

//  Reference from    https://leonardoce.wordpress.com/2015/03/11/dbus-tutorial-using-the-low-level-api/
//                    https://github.com/fbuihuu/samples-dbus
//                  

//  install DBus dev package
sudo apt-get install libdbus-1-dev libdbus-glib-1-dev


//   compile dbus_connection_name.c

gcc -o dbus_connection_name -Wall dbus_connection_name.c `pkg-config --cflags dbus-1` `pkg-config --libs dbus-1`

$ ./dbus_connection_name 
This is my unique name
:1.32

//     
