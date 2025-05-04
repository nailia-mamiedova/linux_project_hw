To run this simple Linux project on your local machine, follow these steps:
1. **Clone the repository**: Use the following command to clone the repository to your local machine:
   
   with *SSH*:
   ```bash
   git clone git@github.com:nailia-mamiedova/linux_project_hw.git
    ```
   *Or HTTPS*:
    ```bash
    git clone https://github.com/nailia-mamiedova/linux_project_hw.git
    ```
2. **Navigate to the project directory**: Change into the project directory using:
    ```bash
   cd linux_project_hw/
   ```
3. **Build the project**: Use the following commands to compile and build the project:
   ```bash
   autoreconf -i
   ./configure
   make
   sudo make install
   ```
4. **Run the project**: After building, you can run the project using:
   ```bash
    helloworld
    ```
5. **Clean up**: To clean up the build files, you can use:
    ```bash
   make clean-all
   ```
