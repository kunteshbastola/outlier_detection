This notebook shows the process of removal of oulier in the dataset. Firstly, the normal distribution is checked using distplot and if data is normally distributed then only the oulier removal
and detection can be used. we calculate if the dataset lies in the range between mean+3*std and mean - 3 *std and the data not in the range is discarded and we can use another method
z- score to calculate the range it is calcualed by (x(individual_value)- mean() )- std and is checked if the dataset lies in the range of 3 and -3 of z score the dataset not in the range is
discarded and capping is also used which removes the anomolies without removing the dataset
