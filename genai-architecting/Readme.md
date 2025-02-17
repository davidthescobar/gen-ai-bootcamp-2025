![screenshot](genai-architecting/genai-architecture.png)

## Functional Requirements

The company wants to invest in owning their infrastructure.
The reason is because there is a concern about the privacy of user
data and also a concern about the cost of managed services for GenAi will
greatly raise in cost. 

They want to invest in an AI-PC where they can afford spend of 10-15k.
They have 300 active students, and students are located within the city
of Tel Aviv, Israel.

## Assumptions

We are assuming that the LLMs will have enough generalized training data
to fully deliver on our functional requirements.

We are assuming that the open-source LLMs that we chose will be powerful
enough to run on hardward with an investment of 10-15k.

We're just going to hook up a single server in our office to the internet
and we should have enough bandwith to serve the 300 students.

## Data Strategy

There is a concern of copyrighted materials, so we must purchase and
supply materials and store them for access in our database.

## Considerations

We're considering using IBM Granite because it is a truly open source
model with training data that is traceable so we can avoid any
copyright issues and we are able to know what is going on in the model.

https://huggingface.co/ibm-granite