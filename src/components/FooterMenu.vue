<template>
    <div class="footer">
        <div class="footer-download">
            <img
                class="phones"
                src="@/assets/images/two-phones@2x.png"
                alt="Çiçeksepetini İndirin"
            />
            <div class="vertical-middle">
                <div class="footer-download-content">
                    <img src="@/assets/images/qr.png" alt="QR Kod" />
                    <div class="footer-download-content-text">
                        <span class="title"
                            >Çiçek Sepeti Mobil Uygulamayı İndirin</span
                        ><br />
                        <span class="title-qr"
                            >Mobil Uygulamayı QR Kod ile İndirin.</span
                        >
                    </div>
                </div>
                <div class="footer-download-content-row">
                    <img src="@/assets/images/playstore.svg" alt="Playstore" />
                    <img
                        src="@/assets/images/appstore.svg"
                        alt="Appstore"
                        class="appstore"
                    />
                </div>
            </div>
        </div>
        <div class="footer-menu">
            <div class="info">
                <img src="@/assets/images/logo.svg" alt="ÇiçekSepeti" class="logo" />
                <div class="buttons">
                    <img src="@/assets/images/facebook.svg" alt="Facebook" />
                    <img src="@/assets/images/twitter.svg" alt="Twitter" />
                    <img src="@/assets/images/instagram.svg" alt="Instagram" />
                    <img src="@/assets/images/youtube.svg" alt="Youtube" />
                    <img src="@/assets/images/blog.svg" alt="Blog" />
                </div>
                <p>
                    hicaku.com olarak kişisel verilerinizin gizliliğini önemsiyoruz. 6698 sayılı Kişisel Verilerin Korunması Kanunu kapsamında oluşturduğumuz aydınlatma metnine <a href="javascript:;">buradan</a> ulaşabilirsiniz.
                </p>
            </div>
            <div class="column">
                <span class="header">Faydalı Bilgiler</span>
                <span class="item">Çiçek Bakımı</span>
                <span class="item">Çiçek Eşliğinde Notlar</span>
                <span class="item">Çiçek Anlamları</span>
                <span class="item">Özel Günler</span>
                <span class="item">Mevsimlere Göre Çiçekler</span>
                <span class="item">BonnyFood Saklama Koşulları</span>
                <span class="item">Site Haritası</span>
            </div>
            <div class="column">
                <span class="header">Kurumsal</span>
                <span class="item">Hakkımızda</span>
                <span class="item">Kariyer</span>
                <span class="item">ÇiçekSepeti’nde Satış Yap</span>
                <span class="item">Kurumsal Müşterilerimiz</span>
                <span class="item">Reklamlarımız</span>
                <span class="item">Basında Biz</span>
                <span class="item">Kampanyalar</span>
                <span class="item">Vizyonumuz</span>
            </div>
            <div class="column">
                <span class="header">İletişim</span>
                <span class="item">Bize Ulaşın</span>
                <span class="item">Sıkça Sorulan Sorular</span>
            </div>
            <div class="column">
                <span class="header">Gizlilik Sözleşmesi</span>
                <span class="item">Mesafeli Satış Sözleşmesi</span>
                <span class="item">Bilgi Toplumu Hizmetleri</span>
                <span class="item">Gizlilik Sözleşmesi</span>
                <span class="item">Ödeme Seçenekleri</span>
                <span class="item">Hesap Bilgileri</span>
            </div>
        </div>
        <p class="description">
            Türkiyenin en büyük online çiçek sitesi ÇiçekSepeti ile sevdiklerinizi mutlu etmek çok kolay! Çiçek göndermenin ve “Mutlu etmenin adresi” Çiçek Sepeti ile sevdiklerinize özel günlerde online çiçek gönderebilirsiniz. Geniş çiçekçi ağı sayesinde çiçek siparişleriniz Türkiye’nin dört bir yanına hızlı ve sorunsuz şekilde gönderilir. Taze çiçeklerle hazırlanan mis kokulu şık çiçek aranjmanları arasından beğendiğiniz ürünü seçerek, hızlı bir şekilde online sipariş verebilirsiniz. Sevdiklerinizin doğum günü, yıldönümü gibi mutlu günlerinde onların sevincine ortak olmak için yapmanız gereken sadece birkaç tıkla sipariş vermek. Sevgililer Günü, Kadınlar Günü, Anneler Günü gibi özel günlerde de çiçek, hediye ve lezzetli bonnyFood ürünleriyle sevdiklerinizi mutlu edebilirsiniz. Çünkü mutlu etmenin adresi; ÇiçekSepeti.
        </p>
    </div>
</template>
<style lang="less" scoped>
.footer {
    margin-top: 100px;
    padding-top: 150px;
    padding-bottom: 50px;
    background: var(--color-white-dark);
    &-download {
        display: flex;
        justify-content: space-evenly;
        background: var(--color-white)fff;
        border-radius: 111px;
        padding: 0 300px;
        height: 200px;
        .phones {
            width: 350px;
            height: 350px;
            margin-top: -155px;
        }
        &-content {
            display: flex;
            img {
                height: 60px;
                width: 60px;
            }
            &-text {
                margin-left: 20px;
                .title {
                    font-size: 18px;
                    font-weight: bold;
                    &-qr {
                        margin-top: 10px;
                        font-size: 16px;
                        font-weight: normal;
                        display: inline-block;
                    }
                }
            }
            &-row {
                margin-top: 30px;
                display: flex;
                gap: 10px;
                img {
                    cursor: pointer;
                    height: 50px;
                    width: 175px;
                    &.appstore {
                        width: 190px;
                    }
                }
            }
        }
    }
    &-menu {
        display: flex;
        justify-content: space-evenly;
        margin-top: 100px;
        .info{
            display: flex;
            flex-direction: column;
            gap: 30px;
            padding-right: 50px;
            border-right: 1px dashed var(--color-gray);
            width: 450px;
            .logo{
                width: 230px;
            }
            .buttons{
                display: flex;
                gap: 30px;
            }
            p{
                margin: 0;
            }
            a {
                color: var(--color-black)
            }
        }
        .column{
            display: flex;
            flex-direction: column;
            gap: 10px;
            text-align: center;
            .header{
                color: var(--color-blue);
                font-size: 18px;
            }
            .item{
                font-size: 16px;
                cursor: pointer;
            }
        }
    }
    .description{
        margin-top: 100px;
        font-size: 15px;
        text-align: center;
        padding: 0 80px;
    }
}
@media screen and (max-width: 1410px) {
    .footer {
        &-download {
            padding: 0 30px;
            .phones{
                display: none;
            }
        }
    }
}
@media screen and (max-width: 650px) {
    .footer {
        &-download {
            height: auto;
            border-radius: 5px;
            &-content {
                flex-direction: column;
                text-align: center;
                img {
                    height: 60px;
                    width: 60px;
                    margin: 10px auto;
                }
                &-text {
                    .title {
                        font-size: 18px;
                        font-weight: bold;
                        &-qr {
                            margin-top: 10px;
                            font-size: 16px;
                            font-weight: normal;
                            display: inline-block;
                        }
                    }
                }
                &-row {
                    gap: 0px;
                    img {
                        margin: 10px auto;
                        cursor: pointer;
                        height: 35px;
                        width: 100px;
                        &.appstore {
                            width: 120px;
                        }
                    }
                }
            }
        }
        &-menu {
            flex-direction: column;
            .info{
                border: none;
                padding-right: 0;
                width: 100%;
                margin-bottom: 50px;
                .logo{
                    margin: 0 auto;
                }
                .buttons{
                    gap: 10px;
                    justify-content: space-between;
                }
                p{
                    text-align: center;
                }
                a {
                    color: var(--color-black)
                }
            }
            .column{
                margin-bottom: 40px;
            }
        }
        .description{
            margin-top: 50px;
            font-size: 18px;
            padding: 0 20px;
        }
    }
}
@media screen and (max-width: 290px) {
    .footer {
        &-download {
            &-content {
                &-row {
                    flex-direction: column;
                }
            }
        }
        &-menu {
            .info{
                .logo{
                    width: 100px;
                }
                .buttons{
                    gap: 10px;
                    justify-content: space-between;
                    img {
                        width: 20px;
                    }
                }
            }
        }
    }
}
</style>
