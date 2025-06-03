def calculate_percentage(person):
    total_marks =sum(person["marks"])
    return(total_marks/4)
a=[
    {"name":"prem","age":19,"marks":[45,50,60,70]},
    {"name":"moni","age":19,"marks":[45,50,50,70]},
    {"name":"nithish","age":19,"marks":[45,50,80,70]},
    {"name":"malai","age":19,"marks":[45,50,65,70]}
]
b=sorted(a, key=calculate_percentage, reverse=True)
pos=1
for i in b:
    if pos==1:
        des="first"
    elif pos==2:
        des="second"
    elif pos==3:
        des="third"
    elif pos==4:
        des="fourth"
    elif pos==5:
        des="fifth"
    percentage = calculate_percentage(i)
    print("{} wit per {:.2f}% stands->{}".format(i["name"],percentage,des))
    pos=pos+1
