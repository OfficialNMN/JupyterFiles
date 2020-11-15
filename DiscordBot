import discord

client=discord.Client()

@client.event
async def on_ready():
    print(f"logged in as {client.user}")

@client.event
async def on_message(message):
    print(f"{message.channel}: {message.author}: {message.author.name}: {message.content}")
    bot_guild=client.get_guild(guild_no.)

    if "hi" in message.content.lower():
        await message.channel.send("Kaisa hai "+message.author.name+" noob")
    elif "bye" in message.content.lower():
        await message.channel.send("Nikal "+message.author.name+" pehli fursat mein")
    elif "!getlost" in message.content.lower():
        await client.close()
    elif "member_count" == message.content.lower():
        await message.channel.send(f"```{bot_guild.member_count}```")
    elif 'happy birthday' in message.content.lower():
        await message.channel.send('Happy Birthday! ')

@client.event
async def on_member_join(member):
    await member.create_dm()
    await member.dm_channel.send(f'Aaja {member.name}, tera hi intezaar tha')


client.run("token_no")

