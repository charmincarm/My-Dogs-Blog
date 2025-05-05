<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Dog's Blog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0d0d0d;
      color: #e6e6ff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4b0082;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #bb86fc;
      border-bottom: 1px solid #333;
      padding-bottom: 5px;
    }
    .photo-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .photo-gallery img {
      width: 100%;
      border-radius: 8px;
      border: 2px solid #333;
    }
    .post {
      background-color: #1a1a1a;
      padding: 15px;
      margin-bottom: 20px;
      border-radius: 8px;
      border-left: 4px solid #bb86fc;
    }
    .comment-section {
      margin-top: 40px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      background-color: #1f1f1f;
      border: 1px solid #444;
      color: #fff;
    }
    button {
      background-color: #4b0082;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      cursor: pointer;
    }
    button:hover {
      background-color: #6a0dad;
    }
    .footer {
      text-align: center;
      padding: 20px;
      color: #999;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Adventures of My Dog</h1>
    <p>Follow the life and thoughts of my four-legged best friend.</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>Hi, I'm the human behind this blog! I created this space to document the funny, adventurous, and heartwarming moments I share with my dog. Whether it's a walk in the park or a nap on the couch, every day is an adventure.</p>
  </section>

  <section>
    <h2>Bio</h2>
    <p><strong>Name:</strong> Max<br/>
    <strong>Breed:</strong> Golden Retriever<br/>
    <strong>Favorite Toy:</strong> Squeaky duck<br/>
    <strong>Hobbies:</strong> Chasing squirrels, belly rubs, and barking at delivery trucks.</p>
  </section>

  <section>
    <h2>Photo Gallery</h2>
    <div class="photo-gallery">
      <img src="https://place-puppy.com/300x300" alt="Dog photo 1" />
      <img src="https://place-puppy.com/301x301" alt="Dog photo 2" />
      <img src="https://place-puppy.com/302x302" alt="Dog photo 3" />
      <img src="https://place-puppy.com/303x303" alt="Dog photo 4" />
    </div>
  </section>

  <section>
    <h2>Blog Posts</h2>
    <div class="post">
      <h3>Max's Muddy Misadventure</h3>
      <p>Today Max found a huge mud puddle and decided it was his personal spa. The cleanup took an hour, but the joy on his face was worth every second.</p>
    </div>
    <div class="post">
      <h3>Park Patrol</h3>
      <p>Max made it his mission to sniff every tree and bark at every squirrel in the park today. Mission accomplished.</p>
    </div>
  </section>

  <section class="comment-section">
    <h2>Leave a Comment</h2>
    <form onsubmit="event.preventDefault(); alert('Thanks for your comment!'); this.reset();">
      <input type="text" placeholder="Your name" required />
      <textarea placeholder="Your comment" rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <div class="footer">
    &copy; 2025 My Dog's Blog. All rights reserved.
  </div>
</body>
</html>
