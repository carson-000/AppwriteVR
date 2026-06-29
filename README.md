# appwriteVR

appwriteVR is a backend service created specifically for VR games. It can be used as an alternative to PlayFab, Firebase, and others.

# Why should I use Appwrite(VR) over alternatives?

## Pricing
Appwrite offers a generous free plan to start off with, but the even better part is that the pro plan is free with GitHub Education! So, if you are enrolled in high school or college, you unlock a free Appwrite Education (equivilent to Pro) plan. With GitHub Education, you also unlock plenty of other things, for example, GitHub Pro, GitHub Copilot Education, free domains while you are a student (from name(.)com and Namecheap), free JetBrains subscription (10+ IDE's, and JetBrains academy), and plenty more. Learn more at https://education.github.com/pack

## Security
Appwrite gives you full control over basically everything, which allows you to give and take access to certain things like databases, using Functions (which appwriteVR uses) you get an API key, and that is the only way to access important information, appwriteVR calls the function API, and it ONLY returns the data that is needed, no client sided access is used at all. For example, PlayFab Unity SDK requires a title id, and gives attackers a full range of calls that can be used at their disposal, with Appwrite, the function gets the data behind the scenes, and the attacker only gets what is served to them.

_currently being developed, check back soon._
