# uptime-callGuard
Voice alert system

This project provides an automated voice alert system that integrates with Uptime Kuma. When an alert is triggered, a webhook sends the alert details to a serverless function (AWS Lambda/Azure Functions). The system then uses AI-powered text-to-speech (TTS) services to generate a voice message, which is played over a Twilio phone call, ensuring immediate notification of downtime events.
Features:

    Webhook listener for Uptime Kuma alerts

    AI-generated voice notifications (Amazon Polly, Azure Speech, ElevenLabs, etc.)

    Twilio integration for automated phone calls

    Cloud deployment on AWS Lambda or Azure Functions

    Secure API access and monitoring

Use Case:

Ideal for system administrators who need instant voice notifications for critical service outages.
