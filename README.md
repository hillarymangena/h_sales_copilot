# h_sales_copilot built using RelevanceAI (Converstational Agent)
Integrations: Fire Crawl (web scraper), OpenAI GPT Models, LinkedIn Data Extraction, Custom Tools

WHAT_IT_DOES

Takes in a prospective client's linkedin profile url, and their company's url, and scrapes data. Then, it summarises this data, and outputs a pre-call sales report that helps the agent acquire the client.
Typical information includes potential selling points, possible objections and how to handle them.

WORK_FLOW

The AI Agent uses 3 separate tools; Lead Recon, Company Recon, and a Pre-sales Report Generator. The Lead Recon tool takes in the prospective client's url and the Company Recon tool takes in the 
company's website url. The output of both tools is used by the Pre-sales Report Generator Tool to generate the final pre-sales report of tailor blueprint on how to close the particular Lead.

TEMPLATE:
https://app.relevanceai.com/agents/d7b62b/b0daed2b-8c47-4b3b-af4e-1d74480850db/7292073a-5d96-4fb7-9584-949060f07315/clone


Try it out here; 
https://app.relevanceai.com/agents/d7b62b/b0daed2b-8c47-4b3b-af4e-1d74480850db/7292073a-5d96-4fb7-9584-949060f07315/embed-chat?hide_tool_steps=false&hide_file_uploads=false&hide_conversation_list=false&bubble_style=agent&primary_color=%23685FFF&bubble_icon=pd%2Fchat&input_placeholder_text=Type+your+message...&hide_logo=false&hide_description=false

To start, just describe briefly that you want a pre-sales report, and provide the linkedin and company website urls. 
Note - response may be slow/unavailable due to limited credits, expired API keys and private linkedin profiles cannot be data scrapped. 
