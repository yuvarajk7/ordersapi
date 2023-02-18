## ordersapi - REST implementation
 
#install package and run
pipenv install --dev && pipenv shell

#run
uvicorn orders.app:app --reload

#browse
http://localhost:8000/docs/orders
