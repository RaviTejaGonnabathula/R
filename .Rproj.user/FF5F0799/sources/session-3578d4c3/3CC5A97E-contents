#Importing CSV file
mydata <- read.csv("Bengaluru_House_Data.csv")


head(mydata)
tail(mydata)
View(mydata)

mydata[1,3]

#installing package tidyverse
install.packages("tidyverse")
library("tidyverse")
require("tidyverse")

glimpse(mydata)

mydata %>%
  select(location,price)%>%
  filter(price < 150 & location == "whitefield")


require("tidyverse")
# returns datasets present in the Library
#data()
#Returns starwars 
#View(starwars)
starwars %>%
  select(gender,mass,height,species)%>%
  filter(species == "Human") %>%
  na.omit() %>%
  mutate(height = height / 100) %>%
  mutate(BMI = mass /height^2 ) %>%
  group_by(gender) %>%
  summarise(Average_BMi = mean(BMI))



