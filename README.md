# Filter & Pagination in Django

- Filter your result-set
- Paginate your result-set as per object you want in your response
- It's a open source service. 
- Easy to implement
- Fastest execution & High performance

---
## Install with pip
```
pip install filter-and-pagination
```

---
## How to implement
- import  FilterPagination
```
from filter_and_pagination import FilterPagination
```

- Used in
```
FilterPagination.filter_and_pagination(request, ModelReference)
```

---
## Demo

 **Request:**
 - URL: http://127.0.0.1:8000/customers/api/v1/?name=jasmin
 - Method: GET

**Response:**
```
{
	"status_code": 200,
	"status": "success",
	"message": [
		"Customer data retrieved successfully."
	],
	"data": {
		"dataset": [{
			"id": 166,
			"name": "Jasmin",
			"full_name": "Jasmin Perry",
			"email": "nicolemathews@smith-anderson.net",
			"contact_no_dail_code": "186",
			"contact_no": "9831999092",
			"dob": "1936-07-27",
			"gender": 1,
			"address": "466 Zuniga Trail Suite 955\nLake Brandonside, AL 22894",
			"extra": {},
			"created_at": "2020-01-11T10:09:24.780734Z",
			"updated_at": "2020-01-11T10:09:24.780745Z"
		}],
		"pagination": {
			"per_page": 20,
			"current_page": 1,
			"total_count": 1,
			"total_pages": 1
		}
	}
}
```

---
### PyPi
- Project: filter-and-pagination
- link: https://pypi.org/project/filter-and-pagination/

---
### GitHub
- Project: filter-pagination-dj
- link: https://github.com/ashish1997it/filter-pagination-dj

---
### PostMan
- Collection: filter-and-pagination-in-GH-proj
- link: https://www.getpostman.com/collections/eae09a934fbc284bc062

---
### Medium
- Article: Filter & Pagination in Django
- link: https://medium.com/@sondagarashish/filter-and-pagination-in-django-c0a61ff5f5c4

---
