# School Library - Walrus Evidence System 🎓

A decentralized application (dApp) designed to preserve student projects and educational resources using the **Walrus Network**. This project features a unique, interactive "Classroom" interface built entirely with CSS art, providing an engaging way to store knowledge forever.

## 🌟 Features

-   **Interactive CSS Art Interface**: A fully responsive classroom environment with interactive elements:
    -   **Scroll**: Upload your "Best Works" to the network.
    -   **Owl**: Learn about the mission of the Free Knowledge Library.
    -   **Notebook**: Review documents and explore the blockchain.
    -   **Magnifying Glass**: Explore blobs on WalrusScan.
-   **Walrus Network Integration**: Upload and store files permanently on the Walrus Testnet.
-   **Sui Wallet Connection**: Connect your Sui wallet to interact with the blockchain (includes a simulation mode for testing).
-   **Immutable Evidence**: Students can upload their projects and receive a permanent Blob ID, ensuring their work is preserved.

## 🛠️ Technologies Used

-   **HTML5**: Semantic structure.
-   **CSS3**: Advanced CSS Art for the visual interface (no images used for the room elements).
-   **JavaScript (Vanilla)**: Logic for interactions, API calls, and wallet connection.
-   **Walrus HTTP Publisher**: API for storing blobs on the Walrus Testnet.

## 🚀 Getting Started

### Prerequisites

-   A modern web browser.
-   (Optional) A Sui Wallet extension (e.g., Sui Wallet, Stashed) for full functionality.
-   Python 3 (for running a local server) or any other static file server.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/DataStorageFantasy.git
    cd DataStorageFantasy
    ```

2.  **Run a local server:**
    You can use Python's built-in HTTP server:
    ```bash
    python3 -m http.server 8000
    ```

3.  **Access the application:**
    Open your browser and navigate to:
    `http://localhost:8000`

## 📖 Usage

1.  **Login**: Select your "School Generation" and enter a "Student Alias" to enter the classroom.
2.  **Explore**: Hover over items in the classroom to see what they do.
3.  **Upload**: Click the **Scroll** on the desk to open the uploader. Drag and drop a file to store it on Walrus.
4.  **Verify**: Once uploaded, you will receive a **Blob ID**. You can verify your file on SuiScan using the provided link.

## 📂 Project Structure

-   `index.html`: The main entry point containing all HTML, CSS, and JavaScript logic.
-   `Code.gs`: (Legacy) Google Apps Script file, currently not in active use for the web version.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Built for the future of decentralized education.*
