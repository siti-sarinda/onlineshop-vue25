<template>
    <main>
    <div class="container">
        <h1>HUBUNGI KAMI JIKA ANDA INGIN BERTANYA</h1>
        <p>berikut kontak kontak yang bisa anda hubungi</p>
    </div>
    <div class="container2">
    <div class="background">
    <div class="text">
        <h1>contact</h1>
        <p>pa abdul : 083122635470</p>
        <p>pa bedul : 083123639420</p>
        <p>pa asep : 083162035480</p>
        <h1>berikan saran atau hanya sekedar bertanya</h1>
        </div>
        </div>
        <div class="border">
        <main class="formulir">
            <h1>kirim pesan</h1>
            <p>nama</p>
            <input type="text" placeholder="nama kamu"/>
            <p>email</p>
            <input type="text" placeholder="email kamu"/>
            <p>pesan</p>
            <input type="text" placeholder="pesan kamu"/>
        </main>
        </div>
        </div>
    </main>
</template>

<style scoped>
.container {
        width: 100%;
        height: 200px;
        background-color: #5798e2;
        text-align: center;
        padding-top: 2rem;
        color: white;
    }

    .container2 {
        display: flex;
        gap :20px;
        margin-left: 10rem;
    }

    .text {
        padding-top: 10px;
        padding-left: 10px;
        font-family: 'Segoe UI';
    }

    .text h1 {
        font-size: 2rem;
        margin-top: 10px;
    }

    .text p {
        font-size: 20px;
        margin-left: 1rem;
    }

    .border {
        display: flex;
        background-color: #5798e2;
        width: 15rem;
        height: 22rem;
        border-radius: 10px;
        margin-top: 10px;
        padding-left: 60px;
        font-size: 18px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .background {
        background-color: #5798e2;
        width: 31rem;
        height: 22rem;
        margin-top: 10px;
        border-radius: 10px;
        padding-left: 5rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
</style>