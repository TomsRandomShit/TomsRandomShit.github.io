<!DOCTYPE html>
<html>
<head>
    <title>Discord Proxy</title>
</head>
<body>
    <script>
        const express = require('express');
        const app = express();
        const bodyParser = require('body-parser');
        const fetch = require('node-fetch');

        app.use(bodyParser.json());

        
        const discordWebhook = "https://discord.com/api/webhooks/1328018631098896445/F0vtfn-su4aF-EY739GDTmBvKzJWKDU1nPorC_ogPheFfMxznTEKcrcHqKhJV6XAah0M";

        app.post('/send', async (req, res) => {
            const { content } = req.body;

            if (!content) {
                return res.status(400).send({ error: 'Content is required!' });
            }

            try {
                const response = await fetch(discordWebhook, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({ content }),
                });

                if (!response.ok) {
                    throw new Error('Failed to send webhook');
                }

                res.status(200).send({ success: true });
            } catch (err) {
                res.status(500).send({ error: err.message });
            }
        });

        app.listen(3000, () => {
            console.log('Server running on port 3000');
        });
    </script>
</body>
</html>
