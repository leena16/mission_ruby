1. What exactly happens when you install ruby?
==> It gets installed in .rbenv folder. when we create ruby file i.e example.rb in any folder then in terminal get ruby interpreter in your PATH where ruby file is located and just type ruby example.rb
2. Where does it get installed?
==> /home/username/.rbenv/shims/ruby
3. What files are installed?
==> ruby
==> irb
==> gems
==> testrb
==> rake
==> erb
==> erd
==> rake
4. How do we get access to Ruby from any location in command prompt?
==> By creating .exe file.
5. How to make hello.rb and hello.cpp files executable from any folder and any path ?
==> tell Bash what to do with our file. To do that, we add (#!/home/username/.rbenv/shims/ruby) to    the very top of our script.
==> add execute permissions: chmod 755 hello.rb
==> rename hello.rb file to just hello_rb.
==> We need to put our file into the folder where ruby is installed. we get get the path by typing "which ruby" in terminal. here it is (/home/username/.rbenv/shims/)
 
