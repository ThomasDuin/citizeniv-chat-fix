# citizeniv-chat-fix
This way no javascript or html can be injected through chat. 

Instead of using .replace('<', '&lt;'); I replaced it with to .replace(/<[^>]+>/g, '');
