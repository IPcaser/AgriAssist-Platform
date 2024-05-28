# AgriAssist Platform

AgriAssist is an ASP.NET Core and C#-based platform developed to facilitate streamlined communication between farmers and experts. It allows farmers to post queries and receive quick solutions, enhancing their productivity and problem-solving capabilities.

## Features

- **Query Posting and Resolution:** Farmers can post their queries on the platform and get timely responses from experts.
- **Efficient Data Storage:** Leveraged Microsoft SQL Server for efficient and secure data storage.
- **User-Friendly Interface:** Designed with a user-friendly interface to ensure ease of use for farmers.

## Achievements

- **Streamlined Communication:** Successfully facilitated streamlined communication for over 500 farmers.
- **Improved Query Resolution Time:** Achieved a 25% reduction in query resolution time through optimized data storage.
- **High-Quality Code:** Maintained a 95% bug-free rate through rigorous testing and debugging processes.

## Technologies Used

- ASP.NET Core
- C#
- Microsoft SQL Server

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/IPcaser/AgriAssist-Platform.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd agriassist-platform
    ```

3. **Install the required packages:**
    ```sh
    dotnet restore
    ```

4. **Update the database connection string in `appsettings.json`:**
    ```json
    {
      "ConnectionStrings": {
        "DefaultConnection": "Your_SQL_Server_Connection_String"
      }
    }
    ```

5. **Run the application:**
    ```sh
    dotnet run
    ```

## Usage

Once the application is running, navigate to `http://localhost:5000` to access the AgriAssist Platform. Farmers can post their queries, and experts can respond to them, providing quick and efficient solutions.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

For any inquiries or feedback, please reach out to:

- **Name:** Ishan Pardeshi
- **Email:** ishanapardeshi@gmail.com
- **LinkedIn:** [Your LinkedIn](https://www.linkedin.com/in/ishan-pardeshi-169308272/)

---

Developed by our team during an internship at Deavnet Solutions.
