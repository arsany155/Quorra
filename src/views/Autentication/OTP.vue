<template>
    <!-- component -->
<div class="relative flex min-h-screen flex-col justify-center overflow-hidden bg-gray-200 py-12" dir="rtl">
    <div class="relative bg-white px-6 pt-10 pb-9 shadow-xl mx-auto w-full max-w-lg rounded-2xl">
        <div class="mx-auto flex w-full max-w-md flex-col space-y-16">
        <div class="flex flex-col items-center justify-center text-center space-y-2">
            <div class="font-semibold text-3xl">
            <p>تحقق من البريد الإلكتروني</p>
            </div>
            <div class="flex flex-row text-sm font-medium text-gray-400">
            <p>لقد قمنا بإرسال رمز إلى بريدك الإلكتروني ba**@user.com</p>
            </div>
        </div>

        <div>
            <form action="" method="post">
            <div class="flex flex-col space-y-16">
                <div class="flex flex-row items-center justify-between mx-auto w-full max-w-xs">
                <div class="w-16 h-16 ">
                    <input class="w-full h-full flex flex-col items-center justify-center text-center px-5 outline-none rounded-xl border border-gray-200 text-lg bg-white focus:bg-gray-50 focus:ring-1 ring-blue-700" type="text" name="" id="">
                </div>
                <div class="w-16 h-16 ">
                    <input class="w-full h-full flex flex-col items-center justify-center text-center px-5 outline-none rounded-xl border border-gray-200 text-lg bg-white focus:bg-gray-50 focus:ring-1 ring-blue-700" type="text" name="" id="">
                </div>
                <div class="w-16 h-16 ">
                    <input class="w-full h-full flex flex-col items-center justify-center text-center px-5 outline-none rounded-xl border border-gray-200 text-lg bg-white focus:bg-gray-50 focus:ring-1 ring-blue-700" type="text" name="" id="">
                </div>
                <div class="w-16 h-16 ">
                    <input class="w-full h-full flex flex-col items-center justify-center text-center px-5 outline-none rounded-xl border border-gray-200 text-lg bg-white focus:bg-gray-50 focus:ring-1 ring-blue-700" type="text" name="" id="">
                </div>
                </div>

                <div class="flex flex-col space-y-5">
                <div>
                    <button style="background-color:#5165FD ;" class="flex flex-row items-center justify-center text-center w-full border rounded-xl outline-none py-5  border-none text-white text-sm shadow-sm">
                    تحقق من الحساب
                    </button>
                </div>

                <div class="flex flex-row items-center justify-center text-center text-sm font-medium space-x-1 text-gray-500 gap-x-1">
                    <p>لم تستلم الرمز؟</p> <a class="flex flex-row items-center text-blue-600" href="http://" target="_blank" rel="noopener noreferrer">إعادة الإرسال</a>
                </div>
                </div>
            </div>
            </form>
        </div>
        </div>
    </div>
</div>

</template>