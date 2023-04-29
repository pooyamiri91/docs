+-----------+             +-------------+
| End-User  |             | Video       |
| Device    |             | Streaming   |
|           |  Video      | Server      |
|           |  Request    |             |
+-----+-----+             +------+------+
|                          |
|                          |
|  Video                   |
|  Request                 |
v                          v
+-----------+             +-------------+
|  Check    |             |   Check     |
|  Video    |             |   Cache     |
|   in      |             |  Availability
|  Cache    |             |             |
+-----+-----+             +------+------+
|                          |
|                          |
|  Video                   |
|  Found in Cache?         |
v                          v
+-----------+             +-------------+
|   Serve   |             | Request     |
|  Video    |             | Video from  |
| from Cache|             | Video       |
|           |             | Publisher   |
+-----+-----+             +------+------+
|                          |
|                          |
|  Video                   |
|  Content                 |
v                          v
+-----------+             +-------------+
|  Stream   |             |   Stream    |
|  Video    |             |   Video     |
|  Content  |             |  Content    |
|           |             |             |
+-----+-----+             +------+------+
|                          |
|                          |
|  Video                   |
|  Streaming               |
v                          v
+-----------+             +-------------+
|  Display  |             | Video       |
|   Video   |             |  Playback   |
|           |             |   End-User  |
|           |             |   Device    |
+-----+-----+             +-------------+
