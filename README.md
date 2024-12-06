<<<<<<< HEAD
# G9-hotel_booking_system

The Hotel Booking Management System is a comprehensive solution designed to manage hotel operations efficiently. It automates core hotel processes, including room bookings, inventory management, customer check-ins/check-outs, billing, and staff management. By centralizing these operations, the system ensures smooth communication and coordination between different departments, enhancing the overall guest experience.

## Key Entities

The system revolves around six primary entities, each with specific roles and attributes:
1. Manager

    * Role: Supervises the hotel's operations, including inventory procurement, staff management, and handling customer complaints.
    * Responsibilities:
        Manage staff and ensure smooth operations.
        Purchase and maintain inventory.
        Record and address customer complaints.

2. Inventory

    * Role: Represents hotel resources like supplies and amenities.
    * Attributes:
        Type: The category of the inventory item (e.g., toiletries, furniture).
        Status: Tracks the current state (e.g., available, in use, or damaged).

3. Rooms

    * Role: Defines the rooms available for customers to book.
    * Attributes:
        Room No: Unique identifier for each room.
        Location: Specifies the physical location of the room.

4. Customer

    * Role: Represents individuals staying at or booking the hotel.
    * Attributes:
        Id: A unique identifier for each customer.
        Name: The customer's full name.
        Tel No: Contact number of the customer.
        Address: The customer's home address.
        Room No: The room assigned to the customer.
    * Responsibilities:
        Check-in and check-out process.
        Pay bills for their stay.

5. Receptionist

    * Role: Acts as the point of contact for customers and manages bookings and bills.
    * Responsibilities:
        Check room availability and assign rooms to customers.
        Book rooms and generate bills for customers.
        Accept and log customer feedback.

6. Bill

    * Role: Manages the financial transactions of customers.
    * Attributes:
        Bill No: A unique identifier for each transaction.
        Customer Name: Links the bill to the respective customer.
    * Purpose: Tracks and generates bills based on the customer's stay.

## How It Works

The **Hotel Booking Management System** connects these entities through well-defined relationships:

    * Managers oversee staff and inventory while ensuring seamless operations.
    * Receptionists handle bookings, assist customers during their stay, and generate bills.
    * Customers interact with receptionists for room bookings and payments.
    * Inventory items support the daily operations of the hotel.
=======
# G9-hotel_booking_system
>>>>>>> origin/main
