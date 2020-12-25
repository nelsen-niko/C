# C
Belajar Bahasa C
1. Download Compiler / Kompilator :
GCC, the GNU Compiler Collection
https://gcc.gnu.org/

1.1 MinGW - Minimalist GNU for Windows
https://osdn.net/projects/mingw/releases/

1.2 Homebrew - For MacOS
https://brew.sh/

1.3 Terminal For Linux (.deb)
sudo apt install gcc

2. Download Text Editor :
2.1 Notepad++ https://notepad-plus-plus.org/
2.2 Atom https://atom.io/
2.3 VS Code https://code.visualstudio.com/
2.4 Sublime Text https://www.sublimetext.com/
2.5 GNU Nano https://www.nano-editor.org/

3. Download C, C++ and Fortran IDE :
3.1 Code::Blocks http://www.codeblocks.org/
3.2 Qt Creator https://www.qt.io/
3.3 MonoDevelop https://www.monodevelop.com/

4. Buat nama_file.c
Program Sederhana di C - Halo Dunia

#include <stdio.h>
int main() {
	printf("Halo Dunia\n");
	return 0;
}

simpan dengan nama "halo.c"

5. Proses....
5.1 Compile/Kompilator :
5.1.1 Windows = gcc halo.c -o halo.exe
5.1.2 Linux = gcc halo.c -o halo
5.1.3 MacOS = gcc halo.c -o halo

5.2 Run/Jalankan Program
5.2.1 Windows = halo
5.2.2 Linux = ./halo
5.2.3 MacOS = ./halo

6. Hasil...
diterminal akan tampil teks "Halo Dunia"
