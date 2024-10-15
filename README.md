# Aryan
symmetrical

CREATE TABLE UDUPItravel
(
    id SERIAL PRIMARY KEY,
    "Name_of_place" varchar(50) NOT NULL,
    "Latitude" decimal(9,6) NOT NULL,
    "Longitude" decimal(9,6) NOT NULL,
    "Nearby"  varchar(200)
);

INSERT INTO UDUPItravel
("Name_of_place", "Latitude", "Longitude", "Nearby")
VALUES
('Udupi Shri Krishna Matha', 13.341167, 74.751833, 'Kanakdasa Mantap'),
('Lord Anantheswara Temple', 13.340250, 74.751667, 'Chandramouleswara temple'),
('Coopn Bank Heritage Museum', 13.342917, 74.750306, NULL),
('Mattu Beach', 13.273639, 74.724972, 'Mattu village'),
('Malpe Beach', 13.361583, 74.697650, 'Balaram Temple, Malpe Tile Factory'),
('Koodlutheertha Falls', 13.412750, 75.121139, NULL),
('Hasta Shilpa Heritage Village Museum', 13.342900, 74.789750, NULL),
('Shri Brahmi Durgaparameswari', 13.711000, 74.910500, 'Kubja River, Kamalashile'),
('Kolluru Shri Mookambika Devi', 13.863250, 74.814444, 'Kodachadri Hill, Mookambika Wildlife Sanctuary'),
('Kapu Beach Road', 13.222361, 74.738056, '130 ft Lighthouse, Goddess Mariamma Temple, Jain Basadis'),
('Shri Chaturmukha Jaina Basadi', 13.208583, 75.005028, '700-Year-Old AnantPadmanabha Temple'),
('MAHE Private University', 13.353389, 74.785500, NULL),
('Anegudde Vinayak Temple Road', 13.567333, 74.701083, NULL),
('St. Mary''s Islands', 13.379250, 74.673250, NULL),
('Malpe Sea Walk', 13.348083, 74.695500, NULL),
('Uppinakudru Island', 13.658222, 74.689389, 'Boat Ride from Malpe Harbour, Gopal Krishna Temple'),
('Karkala Sri Gommateswara Statue', 13.203778, 75.005583, NULL),
('St. Lawrence Minor Basilica Shrine', 13.206000, 74.971500, NULL),
('Kodi Beach', 13.614944, 74.670389, 'Kundapura City'),
('Maravanthe Beach', 13.704833, 74.642333, 'Kodachadri Hills, Sauparnika River, Baindur, Belaka Teertha Falls'),
('Udyavar Beach', 13.296000, 74.718056, NULL),
('Padubidri Beach', 13.130889, 74.762500, NULL),
('SeetaNadi Nature Camp', 13.479833, 75.018833, NULL),
('Kudlu Teertha/Sita Falls', 13.412667, 75.121111, 'Someswara Wildlife Sanctuary, Kudremukh National Park'),
('Manipal Museum Anatomy & Pathology', 13.352611, 74.785500, NULL),
('Manipal Endpoint Park', 13.370167, 74.785333, NULL),
('Kota Shivaram Theme Park', 13.521639, 74.703833, NULL),
('Kshitij Nesara Dhama', 13.873250, 74.604000, 'Ottinene Beach'),
('Belakal Teertha', 13.832750, 74.884250, 'Madur'),
('Barkur', 13.471000, 74.753056, NULL),
('Ambalpadi Temple', 13.337250, 74.730056, NULL),
('Mount Rosary Church', 13.386222, 74.736364, NULL),
('Mahisha Mardini Temple', 13.430222, 74.772833, NULL),
('Pajaka Kshetra', 13.271500, 74.788750, NULL),
('Thonse Naturopathy Hospital', 13.412166, 74.702833, NULL),
('Divine Park, Saligrama', 13.490750, 74.711111, NULL),
('Kodi Bengre', 13.449667, 74.695028, NULL);

SELECT * FROM UDUPItravel
