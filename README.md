# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the Body Mass Index(BMI) in the server side. 


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
    height = float(request.POST.get("height"))
    weight = float(request.POST.get("weight"))
    bmi = weight / (height * height)

    # Print to server console for debugging
    print("Height:", height)
    print("Weight:", weight)
    print("BMI calculated:", bmi)

return render(request, "bmiapp/template.html", {"BMI": bmi})
```

## SERVER SIDE PROCESSING:
<img width="1022" height="526" alt="image" src="https://github.com/user-attachments/assets/e5b7bf57-8197-4814-b614-d954452fa39d" />


## HOMEPAGE:
<img width="1029" height="529" alt="image" src="https://github.com/user-attachments/assets/68179983-0016-4c03-8f1f-388a81f5005c" />



## RESULT:
The program for performing server side processing is completed successfully.
