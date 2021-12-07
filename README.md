A simple "hello" application package built with flatpak on ubuntu linux

STEPS

1. install flatpak on ubuntu linux

    sudo apt apt install flatpak flatpak-builder

2. create a project directory and change directory to project

    mkdir hello_flatpak && cd hello_flatpak

3. create flatpak manifest file or use org.gnu.Hello.yaml manifest file

4. build package

    flatpak-builder [NAME-BUILD-DESTINATION] [MANIFEST-FILE-NAME]