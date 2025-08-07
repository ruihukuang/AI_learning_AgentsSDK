# AI_platform_AgentsSDK  
## lab 1
Context   
OpenAI Agents SDK is used to make an agent with name, instructions and a model gpt-4o-mini. This agent is to tell a joke about Autonomous AI Agents. The tracing is built to enable visualizing and debuging agentic flows.  
Agent running results  
<img width="687" height="231" alt="image" src="https://github.com/user-attachments/assets/3ae58a26-4104-4097-a09f-1927f7f77bbf" />    
Trace results    
<img width="1126" height="537" alt="image" src="https://github.com/user-attachments/assets/79ca9975-41a2-4016-ac95-29434cf0ccc0" />  
## lab 2  
Context  
4 traces are created. 
- The first trace *Parallel cold emails* is to use gpt-4o-mini to write three cold emails for a professional sales agent, a engaging sales agent and a busy sales agent. This process is to run multiple asynchronous tasks concurrently and to gather results of all the tasks as a list.  
- The second trace *Selection from sales people* is to use gpt-4o-mini to select the best email among three cold emails from a professional sales agent, a engaging sales agent and a busy sales agent as the ones in the first trace.  
- The third trace *Sales manager* is to use gpt-4o-mini to select the best email as the ones in step 2 and also to send this email based on SendGrid to a defined email address. This process is to wrap a function with the decorator `@function_tool` and also to convert an agent into a tool.      
- The fourth trace *Automated SDR* is to enable to run gpt-4o-mini models/three sales_agent tools multiple times to generate drafts if the drafts are not satisfying at the first attempt and then to select the best email, and also to use a handoff with the use of gpt-4o-mini to act as a Email Manager to take care of formatting including converting an email to HTML and sending the email based on SendGrid.        
<img width="1197" height="346" alt="image" src="https://github.com/user-attachments/assets/c80bbfb6-f101-443d-ad24-f588947c2f33" />  
## lab 3    
Context  
3 traces are created.  
- The first trace *Automated SDR* is to enable to run models including deepseek-chat, gemini-2.0-flash and llama-3.3-70b-versatile/three sales_agent tools three times at most to generate drafts if the drafts are not satisfying at the first attempt and then to select the best email, and also to use a handoff with the use of gpt-4o-mini to act as a Email Manager to take care of formatting including converting an email to HTML and sending the email based on SendGrid.
- The second trace *Protected Automated SDR* is to     






