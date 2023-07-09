# Association_Rule_Recommendation

## Business Problem

Armut, Turkey's largest online service platform, brings together service providers and those seeking services. It enables easy access to services such as cleaning, renovation, and transportation with just a few taps on your computer or smartphone.

![01_logo_armut_color@2x](https://github.com/sametaydn/Association_Rule_Recommendation/assets/53154449/a4ab4a94-2fda-4346-a822-33ac51e3a71f)

By using the dataset that includes service users, the services they have received, and the categories they belong to, an association rule learning-based product recommendation system is aimed to be created.

## Dataset Story

The dataset consists of the services customers have received and the categories of those services. It also includes the date and time information for each service received.

| UserId | Customer number |
|--------|-----------------|
| ServiceId | Anonymous services belonging to each category. (Example: ServiceId 4 under the Cleaning category represents upholstery cleaning service. The same ServiceId may be found under different categories and represent different services. For example, ServiceId 4 under CategoryId 2 represents furniture assembly.) |
| CategoryId | Anonymous categories. (Example: Cleaning, transportation, renovation category) |
| CreateDate | Date of service purchase |
