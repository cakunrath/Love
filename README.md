# tips and studies

-- HTTP VERBS = Get, Post, Put x Patch, Delete

-- Users (id, name, birthday) 
-- INSERT = POST (/api/users)
INSERT INTO users (name, birthday) VALUES ('Carol', '2000-01-01');

-- Carol = 1 
-- SELECT = GET (/api/users)
SELECT * FROM users;

-- SELECT = GET (/api/users/1)
SELECT * 
FROM users
W ;

-- PUT (/api/users/1)
-- JSON = {"name":"carol", "birthday": "2000-01-01"}
UPDATE Users
SET name = 'Carolina', birthday = '2000-01-01'
WHERE id = 1;

-- PATCH (/api/users/1)
-- JSON = {"name":"carol"}
UPDATE Users
SET name = 'Carolina'
WHERE id = 1;

-- DELETE (/api/users/1)
DELETE FROM Users
WHERE ID = 1