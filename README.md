# Hostel Room Allocator

Hostel Room Allocator is a web application designed to digitalize the hospitality process for group accommodations. The application allows users to upload CSV files to efficiently allocate rooms in hostels while ensuring group members with the same ID stay together and adhere to hostel capacities and gender-specific accommodations.

## Features

- **CSV Upload**: Upload two CSV files, one for group details and another for hostel room capacities.
- **Group Allocation**: Ensure group members with the same ID are allocated together.
- **Capacity Management**: Allocate rooms based on hostel capacities.
- **Gender-Specific Accommodation**: Ensure gender-specific room allocations.
- **User-Friendly Interface**: Simple and intuitive web interface for easy use.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 12.x or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/HostelRoomAllocator.git
    cd hostel-room-allocator
    ```

2. **Install Dependencies**:
    ```sh
    npm install
    ```

3. **Start the Application**:
    ```sh
    npm start
    ```

4. **Access the Application**:
    Open your web browser and navigate to `http://localhost:3000`.

## Usage

1. **Upload CSV Files**:
    - **Groups CSV**: Contains information about the groups and their members.
    - **Hostel Rooms CSV**: Contains information about hostel room capacities and other details.

2. **Review Allocations**:
    - After uploading the files, the system will process the data and allocate rooms accordingly.
    - Review the suggested allocations to ensure they meet the requirements.

3. **Download Results**:
    - Once satisfied with the allocations, download the results for further use.

## CSV File Formats

### Groups CSV

| GroupID | MemberID | Name     | Gender |
|---------|----------|----------|--------|
| 1       | 101      | Alice    | F      |
| 1       | 102      | Bob      | M      |
| 2       | 103      | Charlie  | M      |
| 2       | 104      | David    | M      |

### Hostel Rooms CSV

| RoomID | Capacity | Gender |
|--------|----------|--------|
| 201    | 2        | M      |
| 202    | 2        | F      |
| 203    | 4        | M      |
| 204    | 3        | F      |

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Your Name](mailto:your-email@example.com).

---

Thank you for using Hostel Room Allocator!
