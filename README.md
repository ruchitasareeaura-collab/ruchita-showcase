<!-- Font Awesome CDN (যদি আগে থেকে না থাকে) -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
    /* সোশ্যাল আইকন সেকশন */
    .social-links-container {
        background-color: #ffffff; /* ছবির মতো সাদা ব্যাকগ্রাউন্ড */
        padding: 30px 15px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: flex-start;
        gap: 25px 35px; /* আইকনগুলোর মাঝে দূরত্ব */
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .social-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        color: #1a1a1a; /* কালো রঙ */
        transition: transform 0.2s ease, color 0.2s ease;
    }

    .social-item i {
        font-size: 22px; /* আইকনের সাইজ */
        margin-bottom: 8px;
    }

    .social-item span {
        font-size: 10px;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }

    /* হোভার ইফেক্ট */
    .social-item:hover {
        color: #4a5568; /* হোভার করলে হালকা ধূসর */
        transform: translateY(-3px);
    }

    /* মোবাইলের জন্য */
    @media (max-width: 600px) {
        .social-links-container {
            gap: 15px 20px;
        }
        .social-item i {
            font-size: 18px;
        }
        .social-item span {
            font-size: 9px;
        }
    }
</style>

<!-- সোশ্যাল আইকন HTML -->
<div class="social-links-container">
    
    <!-- Facebook -->
    <a href="https://www.facebook.com/share/1ZyJMqjUBj/" class="social-item" target="_blank">"
        <i class="fab fa-facebook-f"></i>
        <span>Facebook</span>
    </a>

    <!-- Group (Facebook Group) -->
    <a href="https://www.facebook.com/share/g/18VQsJhz7M/" class="social-item" target="_blank">
        <i class="fas fa-users"></i>
        <span>Group</span>
    </a>

    <!-- Instagram -->
    <a href="https://www.instagram.com/ruchitasareeaura01?xtok=b2lvYTlwaXYxbTFk" class="social-item" target="_blank">
        <i class="fab fa-instagram"></i>
        <span>Instagram</span>
    </a>

    <!-- WhatsApp -->
    <a href="#https://whatsapp.com/channel/0029Vb81Y01C1FuL0w0vw01C" class="social-item" target="_blank">
        <i class="fab fa-whatsapp"></i>
        <span>WhatsApp</span>
    </a>

    <!-- Channel (WhatsApp/Telegram Channel - Megaphone icon) -->
    <a href="https://whatsapp.com/channel/0029Vb81Y01C1FuL0w0vw01C" class="social-item" target="_blank">
        <i class="fas fa-bullhorn"></i>
        <span>Channel</span>
    </a>

    <!-- X (Twitter) -->
    <a href="https://x.com/RuchitaSaree01" class="social-item" target="_blank">
        <i class="fab fa-x-twitter"></i>
        <span>X</span>
    </a>

    <!-- Threads -->
    <a href="https://www.threads.com/@ruchitasareeaura01" class="social-item" target="_blank">
        <i class="fab fa-threads"></i>
        <span>Threads</span>
    </a>

    <!-- YouTube -->
    <a href="https://youtube.com/@ruchitasaree_aura?si=-zY4N7g1hilxqRUo" class="social-item" target="_blank">
        <i class="fab fa-youtube"></i>
        <span>YouTube</span>
    </a>

    <!-- Pinterest -->
    <a href="https://pin.it/35IkUnGUO" class="social-item" target="_blank">
        <i class="fab fa-pinterest-p"></i>
        <span>Pinterest</span>
    </a>

    <!-- Daraz (Shopping Bag icon) -->
    <a href="https://www.daraz.com.bd/shop/rg8uz6ji/?spm=a2a0e.pdpii_revamp.seller.1.9aac2e738PrDSR&itemId=1600154280&channelSource=pdp" class="social-item" target="_blank">
        <i class="fas fa-shopping-bag"></i>
        <span>Daraz</span>
    </a>

</div>