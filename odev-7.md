    1-SELECT rating,count(*) from film GROUP by rating 
    2-SELECT replacement_cost ,COUNT(*) FROM film GROUP BY replacement_cost HAVING COUNT(*) > 50
    3-SELECT store_id, count(*) from customer GROUP by store_id
    4-SELECT country_id ,COUNT (*) FROM city GROUP BY country_id ORDER BY COUNT(*) desc LIMIT 1