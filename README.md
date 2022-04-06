# ak
details = details.apply(lambda x : 0   
            if column['College'] == "Retail Policies" & column['Covid_non_covid'] == "Covid" & column['report year'] == "21-22" & column['amt']==0 else sum(column['amt']) , axis = 1)
