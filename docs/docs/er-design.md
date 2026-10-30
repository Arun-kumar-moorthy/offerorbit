Sheet 1: users (yaaru login pannuvaanga)

id	name	email	password_hash
1	Arun	arun@mail.com	(encrypted)

Sheet 2: applications (ovvoru job application)

id	user_id	company	role	status
1	1	Zoho	Java Developer	APPLIED

user_id = 1 na Arun-oda application. Idhu dhaan “relationship”.

Sheet 3: status_history (status eppo maarichu)

application_id	old_status	new_status
1	APPLIED	INTERVIEW

Status values: WISHLIST, APPLIED, INTERVIEW, OFFER, REJECTED