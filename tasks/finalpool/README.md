# Final Pool of Implemented Benchmark Tasks

This directory collects the tasks currently marked as **implemented** in the
Notion `Task Tracker` database. Each subdirectory corresponds to one implemented
task and follows the example task layout under `tasks/examples/`:

- `docs/task.md`
- `docs/agent_system_prompt.md`
- `evaluation/main.py`
- optional workspace/script directories (`initial_workspace`,
  `groundtruth_workspace`, `preprocess`, `user_system_prompt.md`)

## Included implemented task families

- `fan-dev`: coupon-manager, discount-calculator, loyalty-program, price-tracker,
  review-aggregator, wishlist-manager
- `gyy`: blog-engine, cms-builder, content-scheduler, robots-handler,
  sitemap-generator, social-publisher, tag-manager
- `haoze`: media-organizer, streaming-service, subtitle-generator, video-trimmer
- `jl_dev`: canvas-grade-automation, customer-feedback-processor,
  email-classification-system, inventory-management, pdf-report-generator
- `junteng_dev`: booking-system, calendar-sync, contact-manager, customer-portal,
  help-desk, order-processor, product-catalog, reminder-service, shipment-tracker
- `junxian_dev`: qr-generator, social-connector, translation-api
- `lueyang-dev`: activity-logger, client-portal, crm-system, deal-manager,
  email-campaign, follow-up-reminder, lead-tracker, sales-pipeline,
  territory-manager
- `lv`: analytics-dashboard, chat-bot, feedback-collector, insights-engine,
  personalization-service, sentiment-analyzer, survey-builder, voice-processor
- `ruige`: canvas-automation, data-analytics, expense-tracker, file-manager,
  log-analyzer, web-crawler
- `wenshuo-dev`: cache-optimizer, document-parser, image-processor, scheduler,
  search-engine
- `xiaochen_dev`: backup-utility, deployment-tool, error-tracker, health-monitor,
  monitoring-agent, security-scanner, status-checker
- `yuxuan-dev`: asset-optimizer, content-manager, network-analyzer, sync-service,
  task-scheduler
- `yuzhen-dev`: alert-system, audit-logger, data-validator, form-builder,
  invoice-generator, payment-processor, permission-manager, resource-monitor
- `zhaochen`: certificate-manager, load-balancer, storage-manager, template-engine

Tasks still marked **implementing** (e.g. incomplete non-English prompts or
missing scaffold files) remain on their development branches and are not copied
into this pool.
