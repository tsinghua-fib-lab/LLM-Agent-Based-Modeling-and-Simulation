# LLM empowered agent-based modeling and simulation
A summary of works on LLM empowered agent-based modeling and simulation.

Our survey **Large language models empowered agent-based modeling and simulation: a survey and perspectives** is accepted by Humanities and Social Sciences Communications, which is under *Nature*.

A preprint is available on arxiv: [link](https://arxiv.org/pdf/2312.11970)

Please cite our survey paper if you find our work helpful.
```
@article{gao2023large,
  title={Large language models empowered agent-based modeling and simulation: A survey and perspectives},
  author={Gao, Chen and Lan, Xiaochong and Li, Nian and Yuan, Yuan and Ding, Jingtao and Zhou, Zhilun and Xu, Fengli and Li, Yong},
  journal={arXiv preprint arXiv:2312.11970},
  year={2023}
}
```
We will update the journal name after our paper is officially published.

# Table of Contents
- [Challenges and approaches of LLM for ABS](#Challenges-and-approaches-of-LLM-for-ABS)
    - [Environment Construction and Interface](#Environment-Construction-and-Interface)
    - [Human Alignment and Personalization](#Human-Alignment-and-Personalization)
    - [How to simulate actions](#How-to-simulate-actions)
    - [Evaluation of LLM agents](#Evaluation-of-LLM-agents)
- [Recent advances of LLM for ABS](#Recent-advances-of-LLM-for-ABS)
    -  [Social Domain I: Social Sciences](#Social-Domain-I-Social-Sciences)
        - [Social Network Dynamics](#Social-Network-Dynamics)
        - [Cooperation](#Cooperation)
        - [Individual Social Behavior](#Individual-Social-Behavior)
    - [Social Domain II: Economic System](Social-Domain-II-Economic-System)
        - [Individual Economic Behavior](Individual-Economic-Behavior)
        - [Interactive Economic Behavior](Interactive-Economic-Behavior)
        - [Economic System](Economic-System)
    - [Physical Domain](Physical-Domain)
    - [Cyber Domain](Cyber-Domain)
    - [Hybrid Domain](Hybrid-Domain)

## Challenges and approaches of LLM for ABS
   ### Environment Construction and Interface
| **Name** | **Paper** | **Venue** | **Code** |
| --- | --- | --- | --- |
| ChatDev | [Qian, C., Cong, X., Yang, C., Chen, W., Su, Y., Xu, J., ... & Sun, M. (2023). Communicative agents for software development. arXiv preprint arXiv:2307.07924.](https://openreview.net/pdf?id=yW0AZ5wPji) | arxiv | [Python](https://github.com/OpenBMB/ChatDev) |
| RecAgent | [Wang, L., Zhang, J., Chen, X., Lin, Y., Song, R., Zhao, W. X., & Wen, J. R. (2023). Recagent: A novel simulation paradigm for recommender systems. arXiv preprint arXiv:2306.02552.](https://arxiv.org/pdf/2306.02552) | arxiv | |
| Generative Agents| [Park, J. S., O'Brien, J., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023, October). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th annual acm symposium on user interface software and technology (pp. 1-22).](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763) | UIST|[Python](https://github.com/joonspk-research/generative_agents) |
|EconAgent| [Li, N., Gao, C., Li, Y., & Liao, Q. (2023). Large language model-empowered agents for simulating macroeconomic activities. arXiv preprint arXiv:2310.10436.](https://arxiv.org/pdf/2310.10436) |ACL|[Python](https://github.com/tsinghua-fib-lab/ACL24-EconAgents)|
|WebAgent| [Gur, I., Furuta, H., Huang, A. V., Safdari, M., Matsuo, Y., Eck, D., & Faust, A. A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis. In The Twelfth International Conference on Learning Representations.](https://arxiv.org/pdf/2307.12856) |ICLR ||
|UGI| [Xu, F., Zhang, J., Gao, C., Feng, J., & Li, Y. (2023). Urban generative intelligence (ugi): A foundational platform for agents in embodied city environment. arXiv preprint arXiv:2312.11813.](https://arxiv.org/pdf/2312.11813) |Arxiv||
| Generative Agents| [Park, J. S., O'Brien, J., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023, October). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th annual acm symposium on user interface software and technology (pp. 1-22).](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763) | UIST|[Python](https://github.com/joonspk-research/generative_agents) |
|GITM| [Zhu, X., Chen, Y., Tian, H., Tao, C., Su, W., Yang, C., ... & Dai, J. (2023). Ghost in the minecraft: Generally capable agents for open-world environments via large language models with text-based knowledge and memory. arXiv preprint arXiv:2305.17144.](https://arxiv.org/pdf/2305.17144)|Arxiv| |

### Human Alignment and Personalization
| **Name** | **Paper** | **Venue** | **Code** |
| --- | --- | --- | --- |
|| [Akata, E., Schulz, L., Coda-Forno, J., Oh, S. J., Bethge, M., & Schulz, E. (2023). Playing repeated games with large language models. arXiv preprint arXiv:2305.16867.](https://arxiv.org/pdf/2305.16867)|Arxiv| |
|Suspicion-Agent| [Guo, J., Yang, B., Yoo, P., Lin, B. Y., Iwasawa, Y., & Matsuo, Y. (2023). Suspicion-agent: Playing imperfect information games with theory of mind aware gpt-4. arXiv preprint arXiv:2309.17277.](https://arxiv.org/pdf/2309.17277)|Arxiv|[Python](https://github.com/CR-Gjx/Suspicion-Agent) |
|Alpacafarm| [Dubois, Y., Li, C. X., Taori, R., Zhang, T., Gulrajani, I., Ba, J., ... & Hashimoto, T. B. (2024). Alpacafarm: A simulation framework for methods that learn from human feedback. Advances in Neural Information Processing Systems, 36.](https://proceedings.neurips.cc/paper_files/paper/2023/file/5fc47800ee5b30b8777fdd30abcaaf3b-Paper-Conference.pdf)|Neurips|[Python]( https://github.com/tatsu-lab/alpaca_farm) |
| Generative Agents| [Park, J. S., O'Brien, J., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023, October). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th annual acm symposium on user interface software and technology (pp. 1-22).](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763) | UIST|[Python](https://github.com/joonspk-research/generative_agents) |
|Personalized Soups| [Jang, J., Kim, S., Lin, B. Y., Wang, Y., Hessel, J., Zettlemoyer, L., ... & Ammanabrolu, P. (2023). Personalized soups: Personalized large language model alignment via post-hoc parameter merging. arXiv preprint arXiv:2310.11564.](https://arxiv.org/pdf/2310.11564) |Arxiv|[Python](https://github.com/joeljang/RLPHF) |
### How to simulate actions
| **Name** | **Paper** | **Venue** | **Code** |
| --- | --- | --- | --- |
| Generative Agents| [Park, J. S., O'Brien, J., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023, October). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th annual acm symposium on user interface software and technology (pp. 1-22).](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763) | UIST|[Python](https://github.com/joonspk-research/generative_agents) |
|GITM| [Zhu, X., Chen, Y., Tian, H., Tao, C., Su, W., Yang, C., ... & Dai, J. (2023). Ghost in the minecraft: Generally capable agents for open-world environments via large language models with text-based knowledge and memory. arXiv preprint arXiv:2305.17144.](https://arxiv.org/pdf/2305.17144)|Arxiv| |
|Voyager| [Wang, G., Xie, Y., Jiang, Y., Mandlekar, A., Xiao, C., Zhu, Y., ... & Anandkumar, A. Voyager: An Open-Ended Embodied Agent with Large Language Models. Transactions on Machine Learning Research.](https://openreview.net/forum?id=ehfRiF0R3a)|TMLR| [python](https://github.com/MineDojo/Voyager/tree/main/voyager/agents) |
|Adaplanner| [Sun, H., Zhuang, Y., Kong, L., Dai, B., & Zhang, C. (2024). Adaplanner: Adaptive planning from feedback with language models. Advances in Neural Information Processing Systems, 36.](https://proceedings.neurips.cc/paper_files/paper/2023/file/b5c8c1c117618267944b2617add0a766-Paper-Conference.pdf)|Neurips| [python](https://github.com/haotiansun14/AdaPlanner) |
|AucArena| [Chen, J., Yuan, S., Ye, R., Majumder, B. P., & Richardson, K. (2023). Put your money where your mouth is: Evaluating strategic planning and execution of llm agents in an auction arena. arXiv preprint arXiv:2310.05746.](https://arxiv.org/pdf/2310.05746)|Arxiv| [python](https://github.com/jiangjiechen/auction-arena)|
|S3| [Gao, C., Lan, X., Lu, Z., Mao, J., Piao, J., Wang, H., ... & Li, Y. (2023). S $^ 3$: Social-network Simulation System with Large Language Model-Empowered Agents. arXiv preprint arXiv:2307.14984.](https://arxiv.org/pdf/2307.14984)|Arxiv| |
|EconAgent| [Li, N., Gao, C., Li, Y., & Liao, Q. (2023). Large language model-empowered agents for simulating macroeconomic activities. arXiv preprint arXiv:2310.10436.](https://arxiv.org/pdf/2310.10436) |ACL|[Python](https://github.com/tsinghua-fib-lab/ACL24-EconAgents)|
|Reflexion| [Shinn, N., Cassano, F., Gopinath, A., Narasimhan, K., & Yao, S. (2024). Reflexion: Language agents with verbal reinforcement learning. Advances in Neural Information Processing Systems, 36.](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf) |Neurips|[Python](https://github.com/noahshinn024/reflexion)|

### Evaluation of LLM agents
| **Name** | **Paper** | **Venue** | **Code** |
| --- | --- | --- | --- |
|S3| [Gao, C., Lan, X., Lu, Z., Mao, J., Piao, J., Wang, H., ... & Li, Y. (2023). S $^ 3$: Social-network Simulation System with Large Language Model-Empowered Agents. arXiv preprint arXiv:2307.14984.](https://arxiv.org/pdf/2307.14984)|Arxiv| |
|EconAgent| [Li, N., Gao, C., Li, Y., & Liao, Q. (2023). Large language model-empowered agents for simulating macroeconomic activities. arXiv preprint arXiv:2310.10436.](https://arxiv.org/pdf/2310.10436) |ACL|[Python](https://github.com/tsinghua-fib-lab/ACL24-EconAgents)|
|LLM-eval-survey| [Chang, Y., Wang, X., Wang, J., Wu, Y., Yang, L., Zhu, K., ... & Xie, X. (2024). A survey on evaluation of large language models. ACM Transactions on Intelligent Systems and Technology, 15(3), 1-45.](https://dl.acm.org/doi/pdf/10.1145/3641289)|TIST| |
## Recent advances of LLM for ABS
### Social Domain I: Social Sciences
#### Social Network Dynamics
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
||[Schwitzgebel, E., Schwitzgebel, D., & Strasser, A. (2024). Creating a large language model of a philosopher. Mind & Language, 39(2), 237-259.](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/mila.12466)| Mind & Language|Virtual|Conversation and Interaction||
|Werewolf|[Xu, Y., Wang, S., Li, P., Luo, F., Wang, X., Liu, W., & Liu, Y. (2023). Exploring large language models for communication games: An empirical study on werewolf. arXiv preprint arXiv:2309.04658.](https://arxiv.org/pdf/2309.04658)| Arxiv |Virtual|Werewolf game||
||[Acerbi, A., & Stubbersfield, J. M. (2023). Large language models show human-like content biases in transmission chain experiments. Proceedings of the National Academy of Sciences, 120(44), e2313790120.](https://www.pnas.org/doi/full/10.1073/pnas.2313790120)| PNAS |Virtual|Information Propagation||
|MachineSoM|[Zhang, J., Xu, X., & Deng, S. (2023). Exploring collaboration mechanisms for llm agents: A social psychology view. arXiv preprint arXiv:2310.02124.](https://arxiv.org/pdf/2310.02124)| Arxiv |Virtual|Collaboration Mechanism|[Python](https://github.com/zjunlp/MachineSoM)|
||[Suzuki, R., & Arita, T. (2024). An evolutionary model of personality traits related to cooperative behavior using a large language model. Scientific Reports, 14(1), 5989.](https://www.nature.com/articles/s41598-024-55903-y)| Scientific Reports |Virtual|Cooperation and defection||
||[de Zarzà, I., de Curtò, J., Roig, G., Manzoni, P., & Calafate, C. T. (2023). Emergent cooperation and strategy adaptation in multi-agent systems: An extended coevolutionary theory with llms. Electronics, 12(12), 2722.](https://www.mdpi.com/2079-9292/12/12/2722)| Electronics|Virtual|Social interaction||
||[Mukobi, G., Erlebach, H., Lauffer, N., Hammond, L., Chan, A., & Clifton, J. (2023). Welfare diplomacy: Benchmarking language model cooperation. arXiv preprint arXiv:2310.08901.](https://arxiv.org/pdf/2310.08901)|Arxiv|Real|Welfare diplomcy game|[python](https://github.com/mukobi/welfare-diplomacy)|
|S3| [Gao, C., Lan, X., Lu, Z., Mao, J., Piao, J., Wang, H., ... & Li, Y. (2023). S $^ 3$: Social-network Simulation System with Large Language Model-Empowered Agents. arXiv preprint arXiv:2307.14984.](https://arxiv.org/pdf/2307.14984)|Arxiv|Real|Online social network||
|SimReddit| [Park, J. S., Popowski, L., Cai, C., Morris, M. R., Liang, P., & Bernstein, M. S. (2022, October). Social simulacra: Creating populated prototypes for social computing systems. In Proceedings of the 35th Annual ACM Symposium on User Interface Software and Technology (pp. 1-18).](https://dl.acm.org/doi/pdf/10.1145/3526113.3545616)|UIST|Virtual|Online forum||
|GA-MAS| [Cai, J., Li, J., Zhang, M., Li, M., Wang, C. S., & Tei, K. (2024). Language Evolution for Evading Social Media Regulation via LLM-based Multi-agent Simulation. arXiv preprint arXiv:2405.02858.](https://arxiv.org/pdf/2405.02858)|Arxiv|Real|Social media langauge|[python](https://github.com/BlueLinkX/GA-MAS)|
|| [Papachristou, M., & Yuan, Y. (2024). Network Formation and Dynamics Among Multi-LLMs. arXiv preprint arXiv:2402.10659.](https://arxiv.org/pdf/2402.10659)|Arxiv|Real|Social network dynamics||
#### Cooperation
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|COLA| [Lan, X., Gao, C., Jin, D., & Li, Y. (2024, May). Stance detection with collaborative role-infused llm-based agents. In Proceedings of the International AAAI Conference on Web and Social Media (Vol. 18, pp. 891-903).](https://ojs.aaai.org/index.php/ICWSM/article/download/31360/33520)|ICWSM|Real|Cooperative Task Solving |[python](https://github.com/tsinghua-fib-lab/COLA)|
|MAD| [Liang, T., He, Z., Jiao, W., Wang, X., Wang, Y., Wang, R., ... & Shi, S. (2023). Encouraging divergent thinking in large language models through multi-agent debate. arXiv preprint arXiv:2305.19118.](https://arxiv.org/pdf/2305.19118)|Arxiv|Virtual|Cooperative Task Solving |[python](https://github.com/Skytliang/Multi-Agents-Debate)|
| ChatDev | [Qian, C., Cong, X., Yang, C., Chen, W., Su, Y., Xu, J., ... & Sun, M. (2023). Communicative agents for software development. arXiv preprint arXiv:2307.07924.](https://openreview.net/pdf?id=yW0AZ5wPji) | Arxiv | Virtual|Cooperative Task Solving |[Python](https://github.com/OpenBMB/ChatDev) |
|MetaGPT| [Hong, S., Zhuge, M., Chen, J., Zheng, X., Cheng, Y., Wang, J., ... & Schmidhuber, J. MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework. In The Twelfth International Conference on Learning Representations.](https://arxiv.org/pdf/2308.00352?trk=public_post_comment-text) | ICLR | Virtual|Cooperative Task Solving |[Python](https://github.com/geekan/MetaGPT) |
|ChatEval| [Chan, C. M., Chen, W., Su, Y., Yu, J., Xue, W., Zhang, S., ... & Liu, Z. ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate. In The Twelfth International Conference on Learning Representations.](https://openreview.net/pdf?id=FQepisCUWu) | ICLR | Virtual|Cooperative Task Solving ||
|CAMEL| [Li, G., Hammoud, H., Itani, H., Khizbullin, D., & Ghanem, B. (2023). Camel: Communicative agents for" mind" exploration of large language model society. Advances in Neural Information Processing Systems, 36, 51991-52008.](https://proceedings.neurips.cc/paper_files/paper/2023/file/a3621ee907def47c1b952ade25c67698-Paper-Conference.pdf) | Neurips | Virtual|Cooperative Task Solving |[python](https://github.com/camel-ai/camel)|
|AgentVerse| [Li, G., Hammoud, H., Itani, H., Khizbullin, D., & Ghanem, B. (2023). Camel: Communicative agents for" mind" exploration of large language model society. Advances in Neural Information Processing Systems, 36, 51991-52008.](https://arxiv.org/pdf/2308.10848) | Arxiv | Virtual|Cooperative Task Solving |[python](https://github.com/OpenBMB/AgentVerse/)|
|SPP| [Wang, Z., Mao, S., Wu, W., Ge, T., Wei, F., & Ji, H. (2024, June). Unleashing the Emergent Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers) (pp. 257-279).](https://aclanthology.org/2024.naacl-long.15/) |NAACL| Virtual|Cooperative Task Solving |[python](https://github.com/MikeWangWZHL/Solo-Performance-Prompting.git)|
|CoELA| [Zhang, H., Du, W., Shan, J., Zhou, Q., Du, Y., Tenenbaum, J. B., ... & Gan, C. (2023). Building cooperative embodied agents modularly with large language models. arXiv preprint arXiv:2307.02485.](https://openreview.net/forum?id=EnXJfQqy0K) |ICLR| Real|Cooperative Task Solving |[python](https://vis-www.cs.umass.edu/Co-LLM-Agents/)|


#### Individual Social Behavior
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|Humanoid Agents| [Wang, Z., Chiu, Y. Y., & Chiu, Y. C. (2023). Humanoid agents: Platform for simulating human-like generative agents. arXiv preprint arXiv:2310.05418.](https://arxiv.org/pdf/2310.05418) |EMNLP| Virtual|Individual social behavior |[python](https://github.com/HumanoidAgents/HumanoidAgents)|
|SocioDojo| [Cheng, J., & Chin, P. (2024). Sociodojo: Building lifelong analytical agents with real-world text and time series. In The Twelfth International Conference on Learning Representations.](https://openreview.net/pdf?id=s9z0HzWJJp) |ICLR| Real|Individual social behavior |[python](https://github.com/chengjunyan1/SocioDojo)|
|| [Liu, R., Yang, R., Jia, C., Zhang, G., Zhou, D., Dai, A. M., ... & Vosoughi, S. (2023). Training socially aligned language models in simulated human society. arXiv preprint arXiv:2305.16960.](https://arxiv.org/pdf/2305.16960) |Arxiv|Virtual|Individual social behavior ||
|Out of one, many| [Argyle, L. P., Busby, E. C., Fulda, N., Gubler, J. R., Rytting, C., & Wingate, D. (2023). Out of one, many: Using language models to simulate human samples. Political Analysis, 31(3), 337-351.](https://arxiv.org/pdf/2209.06899) |Political Analysis|Virtual|Individual social behavior||
|| [Hämäläinen, P., Tavast, M., & Kunnari, A. (2023, April). Evaluating large language models in generating synthetic hci research data: a case study. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (pp. 1-19).](https://dl.acm.org/doi/pdf/10.1145/3544548.3580688) |CHI|Virtual|Individual social behavior||
|Mind meets machine| [Dhingra, S., Singh, M., Vaisakh, S. B., Malviya, N., & Gill, S. S. (2023). Mind meets machine: Unravelling gpt-4’s cognitive psychology. BenchCouncil Transactions on Benchmarks, Standards and Evaluations, 3(3), 100139.](https://www.sciencedirect.com/science/article/pii/S277248592300056X) |Arxiv|Virtual|Individual social behavior||
|| [Binz, M., & Schulz, E. (2023). Using cognitive psychology to understand GPT-3. Proceedings of the National Academy of Sciences, 120(6), e2218523120.](https://www.pnas.org/doi/full/10.1073/pnas.2218523120) |PNAS|Virtual|Individual social behavior||
|| [Elyoseph, Z., Hadar-Shoval, D., Asraf, K., & Lvovsky, M. (2023). ChatGPT outperforms humans in emotional awareness evaluations. Frontiers in Psychology, 14, 1199058.](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2023.1199058/full) |Front. Psychol.|Virtual|Individual social behavior||
|| [Li, X., Li, Y., Joty, S., Liu, L., Huang, F., Qiu, L., & Bing, L. (2022). Does gpt-3 demonstrate psychopathy? evaluating large language models from a psychological perspective. arXiv preprint arXiv:2212.10529.](https://arxiv.org/pdf/2212.10529) |Arxiv|Virtual|Individual social behavior||
|| [Xie, C., & Zou, D. (2024). A Human-Like Reasoning Framework for Multi-Phases Planning Task with Large Language Models. arXiv preprint arXiv:2405.18208.](https://arxiv.org/pdf/2405.18208) |Arxiv|Virtual|Individual social behavior||
|User-Sim| [Yoon, S. E., He, Z., Echterhoff, J. M., & McAuley, J. (2024). Evaluating Large Language Models as Generative User Simulators for Conversational Recommendation. arXiv preprint arXiv:2403.09738.](https://arxiv.org/pdf/2403.09738) |NAACL|Virtual|Individual social behavior|[python](https://github.com/granelle/naacl24-user-sim)|
### Social Domain II: Economic System
#### Individual Economic Behavior
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
||[Horton, J. J. (2023). Large language models as simulated economic agents: What can we learn from homo silicus? (No. w31122). National Bureau of Economic Research.](https://arxiv.org/pdf/2304.05351) |Arxiv|Virtual|Individual ecomonic behavior||
||[Chen, Y., Liu, T. X., Shan, Y., & Zhong, S. (2023). The emergence of economic rationality of GPT. Proceedings of the National Academy of Sciences, 120(51), e2316205120.](https://www.pnas.org/doi/full/10.1073/pnas.2316205120) |PNAS|Virtual|Individual ecomonic behavior||
||[Geerling, W., Mateer, G. D., Wooten, J., & Damodaran, N. (2023). ChatGPT has aced the test of understanding in college economics: Now what?. The American Economist, 68(2), 233-245.](https://journals.sagepub.com/doi/pdf/10.1177/05694345231169654) |The American Economist|Virtual|Individual ecomonic behavior||
|The wall street neophyte|[Xie, Q., Han, W., Lai, Y., Peng, M., & Huang, J. (2023). The wall street neophyte: A zero-shot analysis of chatgpt over multimodal stock movement prediction challenges. arXiv preprint arXiv:2304.05351.](https://arxiv.org/pdf/2304.05351) |Arxiv|Virtual|Individual market behavior||
||[Faria-e-Castro, M., & Leibovici, F. (2024). Artificial Intelligence and Inflation Forecasts (No. 2023-015).](http://real.stlouisfed.org.s3.amazonaws.com/wp/2023/2023-015.pdf) | |Virtual|Individual market behavior||
||[Bybee, L. (2023). Surveying Generative AI's Economic Expectations. arXiv preprint arXiv:2305.02823.](https://arxiv.org/pdf/2305.02823) |Arxiv |Virtual|Individual market behavior||
#### Interactive Economic Behavior
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
||[Phelps, S., & Russell, Y. I. (2023). Investigating emergent goal-like behaviour in large language models using experimental economics. arXiv preprint arXiv:2305.07970.](https://arxiv.org/pdf/2305.07970) |Arxiv |Virtual|Game theory||
||[Akata, E., Schulz, L., Coda-Forno, J., Oh, S. J., Bethge, M., & Schulz, E. (2023). Playing repeated games with large language models. arXiv preprint arXiv:2305.16867.](https://arxiv.org/pdf/2305.16867) |Arxiv |Virtual|Game theory||
|Suspicion-Agent| [Guo, J., Yang, B., Yoo, P., Lin, B. Y., Iwasawa, Y., & Matsuo, Y. (2023). Suspicion-agent: Playing imperfect information games with theory of mind aware gpt-4. arXiv preprint arXiv:2309.17277.](https://arxiv.org/pdf/2309.17277)|Arxiv|Virtual|Game theory|[Python](https://github.com/CR-Gjx/Suspicion-Agent) |
#### Economic System
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|CompeteAI| [Zhao, Q., Wang, J., Zhang, Y., Jin, Y., Zhu, K., Chen, H., & Xie, X. (2023). Competeai: Understanding the competition behaviors in large language model-based agents. arXiv preprint arXiv:2310.17512.](https://arxiv.org/pdf/2310.17512)|Arxiv|Virtual|Consumption market|[Python](https://github.com/microsoft/competeai)|
|SABM| [Han, X., Wu, Z., & Xiao, C. (2023). " Guinea Pig Trials" Utilizing GPT: A Novel Smart Agent-Based Modeling Approach for Studying Firm Competition and Collusion. arXiv preprint arXiv:2308.10974.](https://arxiv.org/pdf/2308.10974)|Arxiv|Virtual|Consumption market|[Python](https://github.com/Roihn/SABM)|
|SABM| [Nascimento, N., Alencar, P., & Cowan, D. (2023, September). Self-adaptive large language model (llm)-based multiagent systems. In 2023 IEEE International Conference on Autonomic Computing and Self-Organizing Systems Companion (ACSOS-C) (pp. 104-109). IEEE.](https://arxiv.org/pdf/2307.06187)|Arxiv|Virtual|Consumption market||
|AucArena| [Chen, J., Yuan, S., Ye, R., Majumder, B. P., & Richardson, K. (2023). Put your money where your mouth is: Evaluating strategic planning and execution of llm agents in an auction arena. arXiv preprint arXiv:2310.05746.](https://arxiv.org/pdf/2310.05746)|Arxiv|Virtual|Auction market|[python](https://github.com/jiangjiechen/auction-arena)|
### Physical Domain
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|LM-NAV| [Shah, D., Osiński, B., & Levine, S. (2023, March). Lm-nav: Robotic navigation with large pre-trained models of language, vision, and action. In Conference on robot learning (pp. 492-504). PMLR.](https://proceedings.mlr.press/v205/shah23b/shah23b.pdf)|CoRL|Real|Navigation behavior|[python](https://sites.google.com/view/lmnav)|
|NLMap| [Chen, B., Xia, F., Ichter, B., Rao, K., Gopalakrishnan, K., Ryoo, M. S., ... & Kappler, D. (2023, May). Open-vocabulary queryable scene representations for real world planning. In 2023 IEEE International Conference on Robotics and Automation (ICRA) (pp. 11509-11522). IEEE.](https://arxiv.org/pdf/2209.09874)|ICRA|Real|Navigation behavior||
|| [Zou, H., Zhao, Q., Bariah, L., Bennis, M., & Debbah, M. (2023). Wireless multi-agent generative ai: From connected intelligence to collective intelligence. arXiv preprint arXiv:2307.02757.](https://arxiv.org/pdf/2307.02757)|ICRA|Real|Wireless network users||
|| [Cui, C., Ma, Y., Cao, X., Ye, W., & Wang, Z. (2024). Drive as you speak: Enabling human-like interaction with large language models in autonomous vehicles. In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (pp. 902-909).](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Cui_Drive_As_You_Speak_Enabling_Human-Like_Interaction_With_Large_Language_WACVW_2024_paper.pdf)|CVPR|Real|Vehicle drivers||
|GITM| [Zhu, X., Chen, Y., Tian, H., Tao, C., Su, W., Yang, C., ... & Dai, J. (2023). Ghost in the minecraft: Generally capable agents for open-world environments via large language models with text-based knowledge and memory. arXiv preprint arXiv:2305.17144.](https://arxiv.org/pdf/2305.17144)|Arxiv|Real|Tool-usage in sandbox game||
### Cyber Domain
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|WebAgent| [Gur, I., Furuta, H., Huang, A. V., Safdari, M., Matsuo, Y., Eck, D., & Faust, A. A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis. In The Twelfth International Conference on Learning Representations.](https://arxiv.org/pdf/2307.12856) |ICLR |Real|Human behaviors in Web|
|Mind2Web| [Deng, X., Gu, Y., Zheng, B., Chen, S., Stevens, S., Wang, B., ... & Su, Y. (2024). Mind2web: Towards a generalist agent for the web. Advances in Neural Information Processing Systems, 36.](https://proceedings.neurips.cc/paper_files/paper/2023/file/5950bf290a1570ea401bf98882128160-Paper-Datasets_and_Benchmarks.pdf) |Neurips |Real|Human behaviors in Web|[python](https://osu-nlp-group.github.io/Mind2Web)|
|WebArena| [Zhou, S., Xu, F. F., Zhu, H., Zhou, X., Lo, R., Sridhar, A., ... & Neubig, G. (2023). Webarena: A realistic web environment for building autonomous agents. arXiv preprint arXiv:2307.13854.](https://arxiv.org/pdf/2307.13854) |ICLR |Real|Human behaviors in Web|[python](https://webarena.dev/)|
|ChoiceMates| [Park, J., Min, B., Ma, X., & Kim, J. (2023). Choicemates: Supporting unfamiliar online decision-making with multi-agent conversational interactions. arXiv preprint arXiv:2310.01331.](https://arxiv.org/pdf/2310.01331) |Arxiv|Real|Human behaviors in Web|
| RecAgent | [Wang, L., Zhang, J., Chen, X., Lin, Y., Song, R., Zhao, W. X., & Wen, J. R. (2023). Recagent: A novel simulation paradigm for recommender systems. arXiv preprint arXiv:2306.02552.](https://arxiv.org/pdf/2306.02552) | Arxiv |Virtual|Interaction with recommender system|
|Agent4Rec | [Zhang, A., Chen, Y., Sheng, L., Wang, X., & Chua, T. S. (2024, July). On generative agents in recommendation. In Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 1807-1817).](https://dl.acm.org/doi/pdf/10.1145/3626772.3657844) | SIGIR |Virtual|Interaction with recommender system|
### Hybrid Domain
| **Name** | **Paper** | **Venue** |**Environment**|**What to Simulate**| **Code** |
| --- | --- | --- | --- | --- | --- |
|GABM-Epidemic| [Williams, R., Hosseinichimeh, N., Majumdar, A., & Ghaffarzadegan, N. (2023). Epidemic modeling with generative agents. arXiv preprint arXiv:2307.04986.](https://arxiv.org/pdf/2307.04986) |Arxiv|Virtual|Epidemic spreading|[python](https://github.com/bear96/GABM-Epidemic)
| Generative Agents| [Park, J. S., O'Brien, J., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023, October). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th annual acm symposium on user interface software and technology (pp. 1-22).](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763) | UIST|Virtual|Sandbox social life|[Python](https://github.com/joonspk-research/generative_agents)|
|WarAgent| [Hua, W., Fan, L., Li, L., Mei, K., Ji, J., Ge, Y., ... & Zhang, Y. (2023). War and peace (waragent): Large language model-based multi-agent simulation of world wars. arXiv preprint arXiv:2311.17227.](https://arxiv.org/pdf/2311.17227) |Arxiv |Real|War simulation|[Python](https://github.com/agiresearch/WarAgents)|
|EconAgent| [Li, N., Gao, C., Li, Y., & Liao, Q. (2023). Large language model-empowered agents for simulating macroeconomic activities. arXiv preprint arXiv:2310.10436.](https://arxiv.org/pdf/2310.10436) |ACL|Real|Macroeconomics|[Python](https://github.com/tsinghua-fib-lab/ACL24-EconAgents)||
|UGI| [Xu, F., Zhang, J., Gao, C., Feng, J., & Li, Y. (2023). Urban generative intelligence (ugi): A foundational platform for agents in embodied city environment. arXiv preprint arXiv:2312.11813.](https://arxiv.org/pdf/2312.11813) |Arxiv|Real|Human behaviors in real-world city||
