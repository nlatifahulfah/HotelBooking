# HotelBooking
**Query yang udah dibuat**

- addAvailability (`room_id`, `check_in`, `check_out`)
- addRoom (`type`)
- getAvailability
- getRoom
- getAllRoomTypeAvailable
    mencari semua **room yang available** (**type apapun**) berdasarkan input `check_in` dan `check_out` pengguna
- getRoomTypeAvailable
    mencari **room yang available** berdasarkan input `type`, `check_in` dan `check_out` pengguna
	
**Type room** (yang udah ditambahin)

- Single
- Double
- Triple
- Quad

**Format input check_in/check_out**

- YYYY-MM-DD**T**hh:mm:ss