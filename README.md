# SQL7
Homework-7-in-kodluyoruz



select rating from film
group by rating;



select replacement_cost, count(*) from film
group by replacement_cost
having count(*) > 50;

select store_id ,count(store_id) from customer
group by store_id ;


select country_id ,count(*) from city
group by country_id 
order by  count(*) Desc
limit 1 ;
