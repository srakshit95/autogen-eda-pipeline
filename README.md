<Project>
  <Title>AutoGen EDA Pipeline</Title>
  <Tagline>Multi-agent system for automated exploratory data analysis and reporting</Tagline>

  <Overview>
    This project leverages Microsoft AutoGen multi-agent architecture to automate exploratory data analysis (EDA) for large datasets.
    It reduces manual analysis time and improves insights generation speed for business users.
  </Overview>

  <Problem>
    <Point>Data scientists spend 40–60% of project time on repetitive EDA tasks.</Point>
    <Point>Business stakeholders often struggle to interpret raw statistical outputs.</Point>
  </Problem>

  <Solution>
    <Step>Built a multi-agent system using AutoGen where one agent generates statistical summaries &amp; charts and another interprets results in plain language.</Step>
    <Step>Configured an iterative feedback loop where agents refine outputs until insights are actionable.</Step>
  </Solution>

  <Impact>
    <Metric>Reduced manual EDA time by ~70%</Metric>
    <Metric>Enabled faster hypothesis validation for marketing and finance analytics teams</Metric>
  </Impact>

  <TechStack>
    <Tool>AutoGen</Tool>
    <Tool>Python</Tool>
    <Tool>Pandas</Tool>
    <Tool>Matplotlib</Tool>
    <Tool>LangChain</Tool>
  </TechStack>

  <Architecture>
    User → AutoGen Controller → EDA Agent (Summaries &amp; Charts) → Insight Agent (Narration &amp; Refinement) → Output Report
  </Architecture>

  <SetupUsage>
    <Step>Clone the repository: `git clone https://github.com/soubhik9/autogen-eda-pipeline.git`</Step>
    <Step>Install dependencies: `pip install -r requirements.txt`</Step>
    <Step>Run the pipeline: `python src/main.py`</Step>
  </SetupUsage>

  <Author>
    <Name>Soubhik Rakshit</Name>
    <Role>AI Product Manager | Data Strategy &amp; GenAI</Role>
    <Links>
      <LinkedIn>http://www.linkedin.com/in/soubhikrakshit95</LinkedIn>
      <Portfolio>https://soubhik-portfolio.designfolio.me/</Portfolio>
    </Links>
  </Author>
</Project>
