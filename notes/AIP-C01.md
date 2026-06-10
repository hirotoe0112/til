## SageMaker

- [Asynchronous inference - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/async-inference.html)
- [Inference options in Amazon SageMaker AI - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/deploy-model-options.html)
- [Deploy models with Amazon SageMaker Serverless Inference - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/serverless-endpoints.html)
- [Real-time inference - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/realtime-endpoints.html)
  - リアルタイムインファレンスは25MBまで
- [Batch transform for inference with Amazon SageMaker AI - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/batch-transform.html)
- [Deploy models with DJL Serving - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/deploy-models-frameworks-djl-serving.html)
- [Inference optimization for Amazon SageMaker AI models - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/model-optimize.html)
- [Model deployment options in Amazon SageMaker AI - Amazon SageMaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-deployment.html)
  - SageMaker AI real-time endpointは使っていない時間にもコストがかかる

## Bedrock

- [Construct and store reusable prompts with Prompt management in Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-management.html)
- [Increase throughput with cross-Region inference - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/cross-region-inference.html)
- [Understanding intelligent prompt routing in Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-routing.html)
  - 少なくとも二つの異なるFMが必要（完全に同一ではない）
  - intelligent prompt routingは同じモデルファミリーの中でしかルーティングできない
- [Increase model invocation capacity with Provisioned Throughput in Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prov-throughput.html)
- [Monitor Amazon Bedrock API calls using CloudTrail - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/logging-using-cloudtrail.html)
- [Monitor model invocation using CloudWatch Logs and Amazon S3 - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/model-invocation-logging.html)
- [Evaluate the performance of Amazon Bedrock resources - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/evaluation.html)
- [Monitor Amazon Bedrock Guardrails using CloudWatch metrics - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/monitoring-guardrails-cw-metrics.html)
- [converse — AWS CLI 2.34.62 Command Reference](https://docs.aws.amazon.com/cli/latest/reference/bedrock-runtime/converse.html)
- [converse - Boto3 1.43.23 documentation](https://docs.aws.amazon.com/boto3/latest/reference/services/bedrock-runtime/client/converse.html)
- [Get started without the AgentCore CLI - Amazon Bedrock AgentCore](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/getting-started-custom.html)
- [Overview - Amazon Bedrock AgentCore](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/what-is-bedrock-agentcore.html)
- [Improve the relevance of query responses with a reranker model in Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/rerank.html)
  - リランカーモデルはクエリとチャンクとの関連性を評価して関連順に並び替える
- [KnowledgeBaseVectorSearchConfiguration - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_agent-runtime_KnowledgeBaseVectorSearchConfiguration.html)
- [Identity and access management for Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/security-iam.html)
- [From RAG to fabric: Lessons learned from building real-world RAGs at GenAIIC – Part 1 | Artificial Intelligence](https://aws.amazon.com/jp/blogs/machine-learning/from-rag-to-fabric-lessons-learned-from-building-real-world-rags-at-genaiic-part-1/)
- [Actions, resources, and condition keys for Amazon Bedrock - Service Authorization Reference](https://docs.aws.amazon.com/service-authorization/latest/reference/list_amazonbedrock.html#amazonbedrock-bedrock_PromptRouterArn)
- [Enforce the use of specific guardrails in model inference requests - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails-permissions-id.html)
- [How Amazon Bedrock works with IAM - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/security_iam_service-with-iam.html)
- [Ingest changes directly into a knowledge base - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/kb-direct-ingestion.html)
- [Design a prompt - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/design-a-prompt.html)
- [Request and Response - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/model-parameters-anthropic-claude-messages-request-response.html)
- [Influence response generation with inference parameters - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-parameters.html#inference-randomness)
- [Include metadata in a data source to improve knowledge base query - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/kb-metadata.html)
- [Use an inference profile in model invocation - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles-use.html)
- [StartAsyncInvoke - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_StartAsyncInvoke.html)
  - このメソッドはAmazon Nova Reel video generationのみサポート
- [Process multiple prompts with batch inference - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/batch-inference.html)
  - area-specific inference profilesを使うことで複数の地域に分散することができる
- [Prerequisites for your Amazon Bedrock knowledge base data - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/knowledge-base-ds.html)
  - Bedrock KBはドキュメント取り込みのサイズにクォータがある
- [Use contextual grounding check to filter hallucinations in responses - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails-contextual-grounding-check.html)
  - GuardRailsにはgrounding checkもある
- [Transform unstructured data into meaningful insights using Amazon Bedrock Data Automation - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/bda.html)
  - Bedrock Data Automationはドキュメントや画像などのデータから情報を抽出するためのサービス
- [Use prompt datasets for model evaluation in Amazon Bedrock - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/model-evaluation-prompt-datasets.html)
  - Automatic Model Evaluationはデータセット1,000まで
- [Prompt caching for faster model inference - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-caching.html)
- [Customize your model to improve its performance for your use case - Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/custom-models.html)
  - fine-tuningはlabeledデータが必要、distillationは大きなモデルから小さなモデルへ知識を転送することで、モデルの圧縮や効率性を目的にして行う
- [Microsoft - Amazon Bedrock AgentCore](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/identity-idp-microsoft.html)
  - AgentCoreではMicrosoft Entra IDをインバウンドIdPとして使用できる

## Amazon Q Developer

- [Reviewing code with Amazon Q Developer - Amazon Q Developer](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/code-reviews.html)
- [Best practices for code generation with Amazon Q Developer - AWS Prescriptive Guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-code-generation/code-generation.html)
- [AI for Software Development – Amazon Q Developer Features – AWS](https://aws.amazon.com/jp/q/developer/features/)

## OpenSearch

- [Learning to Rank for Amazon OpenSearch Service - Amazon OpenSearch Service](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/learning-to-rank.html)
- [Working with vector search collections - Amazon OpenSearch Service](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/serverless-vector-search.html)

## S3

- [Working with S3 Vectors and vector buckets - Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors.html)
- [Event notification types and destinations - Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/userguide/notification-how-to-event-types-and-destinations.html#supported-notification-destinations)
  - S3 Event NotificationのtargetはSQS、SNS、Lambda、EventBridgeのみでStepFunctionsは直接起動できない
- [Working with object metadata - Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingMetadata.html)
  - システム定義メタデータは作成日やサイズなど、ユーザ定義メタデータはアップロード時にユーザが設定できる

## Amazon Nova

- [What is Amazon Nova? - Amazon Nova](https://docs.aws.amazon.com/nova/latest/userguide/what-is-nova.html)
  - Nova Microはtextオンリー

## Lambda

- [Creating and managing Lambda function URLs - AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/urls-configuration.html)

## Amazon Comprehend

- [Detecting PII entities - Amazon Comprehend](https://docs.aws.amazon.com/comprehend/latest/dg/how-pii.html)

## Amazon Textract

- [What is Amazon Textract? - Amazon Textract](https://docs.aws.amazon.com/textract/latest/dg/what-is.html)

## Amazon Macie

- [Discovering sensitive data with Macie - Amazon Macie](https://docs.aws.amazon.com/macie/latest/user/data-classification.html)

## CloudWatch

- [Application Signals - Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Application-Monitoring-Sections.html)
- [Generative AI observability - Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/GenAI-observability.html)

## Step Functions

- [Invoke and customize Amazon Bedrock models with Step Functions - AWS Step Functions](https://docs.aws.amazon.com/step-functions/latest/dg/connect-bedrock.html)
- [Choosing workflow type in Step Functions - AWS Step Functions](https://docs.aws.amazon.com/step-functions/latest/dg/choosing-workflow-type.html)
  - Expressタイプは5分まで
  - Standardタイプは同期実行のみ

## Amazon Aurora

- [Using Aurora PostgreSQL as a Knowledge Base for Amazon Bedrock - Amazon Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/AuroraPostgreSQL.VectorDB.html)

## Amazon Quick

- [What is Amazon Quick? - Amazon Quick](https://docs.aws.amazon.com/quick/latest/userguide/what-is.html)
- [Gaining insights with machine learning (ML) in Amazon Quick Sight - Amazon Quick](https://docs.aws.amazon.com/quick/latest/userguide/making-data-driven-decisions-with-ml-in-quicksight.html)

## Rekognition

- [What is Amazon Rekognition Custom Labels? - Rekognition](https://docs.aws.amazon.com/rekognition/latest/customlabels-dg/what-is.html)

## Amazon Managed Grafana

- [Extend your workspace with plugins - Amazon Managed Grafana](https://docs.aws.amazon.com/grafana/latest/userguide/grafana-plugins.html)

## Amazon DocumentDB

- [Querying in Amazon DocumentDB - Amazon DocumentDB](https://docs.aws.amazon.com/documentdb/latest/devguide/querying.html)

## Glue

- [AWS Glue Data Catalog - AWS Prescriptive Guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/serverless-etl-aws-glue/aws-glue-data-catalog.html)

## General

- [What is Embedding? - Embeddings in Machine Learning Explained - AWS](https://aws.amazon.com/what-is/embeddings-in-machine-learning/)
