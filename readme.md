# Go Booking API

## DB Model

```
hotels
    id
    name
    address
    stars
rooms
    id
    type
    price
    hotel_id
bookings
    id
    arrival
    departure
    guest_id
    room_id
guests
    id
    name
    phone
```