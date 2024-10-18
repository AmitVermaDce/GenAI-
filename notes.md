Langchain


# Generative AI: 
        LLM --> It does have limited powers

    Many APIs:
    1. Open AI
    2. Llama
    3. Mistral
    4. so on

# Problem:
1. LLM has limited context window(input limit)
2. Outdated Knowledge Base
3. Data Privacy
4. Cost of running LLM is very high and training too
5. No Connection with third party tools(real-time connections with APIs or third party tools)
6. so on.....



With so many limitation building a Gen AI based application is not feasible for real-time applications

# Gen AI apps: Lets say we have to build a Gen AI based application so below list of functionalities we need in it

# Data input         # Actions of application                     # Data Output
  1. TXT               1. RAG                                     anything of output format
  2. PDF               2. Agents
  3. SQL               3. APIs
  4. XLS               4. format data
  5. HTML              5. Manipulate
  6. PNG               6. Store
  SO ON..              7. Must have memory to store
                       8. Must have third party tools 
                       and so on..


For Open AI different framework is available
For Llama a different framework is available
For Mistral a different framework is available

To load different models under one framework we can use Langchain 
Other frameworks also available which is LlamaIndex



# Advantages of LangChain
- Langchain is an orchestration framework
    - Langsmith(Monitoring)                 |
    - LangSense(Deployment)                 | LLM Ops
    - LangGraph(Agents)                     |

Lets say we have to build an Generative AI application and it must have multiagents functionality
Then we can use LangGraph and Llamaindex doesn't support LangGraph

Lets say we want to create a POC for an API for the application
Then we can use LangSense

Lets say we want to monitor our application
Then we can use LangSmith


CrewAI is also one such framework using which we can create Agent and MultiAgent
CrewAI is a high level framework built on top of Langchain and easy to understand



# LangChain Evolution
There are two types of models
1. Completion Model
2. Chat Model

Evolution is from
1. From LLM model to chat model
2. From legacy to LangChain Expression language
3. From LangChain to Langchain ecosystem( which is LangSmith, LangSense, LangGraph)



# Completions models are just generation model where no conversation can be done
# Chat models are Chat Completion model. All models available(Mistral, Llama) are chat completion models and this model can take two type of instructions
1. System Instruction(Type of task we want to perform)
2. User Instruction

What is the difference between Legacy LangChain and  Langchain expression language


# Learning Path
1. Introduction
2. How to talk with different LLM(Open AI / Open Source)
3. How to work with Data - Basic of RAG
4. Chains | Runables
5. memory (Stroing previous queries)
6. Ecosystem 
    - LangSmith
    - LangServe
    - LangGraph
7. Level 1 Application
8. Level 2 Application
9. Level 3 Application


# How to Talk with LLM with Langchain
- Connect with the most useful LLM - OpenAI
- Connect with alternative LLMs - OpenSource LLM
- Talk to LLMs in different languages(other than English)
- Introduction to Prompt Template
- Chains
- Output Parser


# prompt: Programming language for LLM to perform communication
# Prompt Template: 
    > Tell me about the history of ....India....
    > Tell me about the history of ....England...
    > Tell me about the history of ....Europe....

    So instead of repeating same question we use prompt template
    > Tell me about the history of {variable}


# Prompts Engineering
1. Zero shot prompting
2. few-shot prompting



