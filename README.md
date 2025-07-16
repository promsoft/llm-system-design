# llm-system-design

Вообще, пока мысль, что надо делать апдейт ML System Design дока, где основной апдейт будет в части про компоненты решения и полезные ссылки, как и что в них продумать. 
Плюс отдельный раздел про evaluation с отличием от классического ML Design Doc в том, что в его проработке обязательно и критично участие бизнеса. 

## LLM System Design components

1) https://skphd.medium.com/llm-system-design-a-complete-guide-to-building-scalable-intelligent-ai-applications-38431bcc1f87 - про компоненты ллм систем дизайна. Надо докручивать, но для старта неплохо.
2) https://medium.com/@zbabar/a-systems-design-approach-to-designing-llm-applications-941f61d5fbe6 - тоже про этапы дизайна, со взглядом про подготовку данных и мониторинг их качества (редко, кто об этом думает заранее)
3) https://murraycole.com/posts/llm-system-design - структурный взгляд на компоненты. Но много для тех, кто дообучает+тюнит модели (мало компаний в РФ готовы в это вкладываться мощностями).

## LLM evaluation

1) https://www.evidentlyai.com/llm-guide/llm-evaluation-metrics - материалы от evidently AI - очень емко, просто и структурно

### RAG evaluation
1) https://medium.com/@med.el.harchaoui/rag-evaluation-metrics-explained-a-complete-guide-dbd7a3b571a8 - Хорошее техническое описание метрик Retrieval и Generated компонент RAG
2) https://qdrant.tech/blog/rag-evaluation-guide/ - комплексное описание метрик. Не только технические, но и метрики результата и системы (вкл. latency). Плюс интересный обзор либ и фреймворков по RAG Evaluation

## Production кейсы

1) https://github.com/themanojdesai/genai-llm-ml-case-studies - репозиторий LLM-кейсов - поверх кейсов от Evidently AI

## Prompt Engineering

Надо добавить ссылки на какие-то гайды
