    1-SELECT avg(rental_rate) from film
    2-SELECT count(*) from film WHERE title like 'C%'
    3-SELECT max(length) from film where rental_rate in (0.99)
    4-SELECT count(DISTINCT(replacement_cost)) from film where length > 150