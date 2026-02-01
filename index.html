<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cheap Data Center GH</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; 
            background-color: #020617; 
            color: #f8fafc; 
            margin: 0;
            overflow-x: hidden;
        }
        .glass { background: rgba(15, 23, 42, 0.6); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.05); }
        .card-glow { transition: all 0.3s ease; }
        .card-glow:hover { border-color: rgba(99, 102, 241, 0.4); box-shadow: 0 0 20px rgba(99, 102, 241, 0.1); }
        ::-webkit-scrollbar { width: 4px; }
        ::-webkit-scrollbar-track { background: #020617; }
        ::-webkit-scrollbar-thumb { background: #334155; border-radius: 10px; }
        .gradient-text { background: linear-gradient(135deg, #6366f1 0%, #a855f7 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        .animate-fade-in { animation: fadeIn 0.4s ease-out forwards; }
        
        @keyframes pulse-soft { 0%, 100% { opacity: 1; } 50% { opacity: 0.6; } }
        .animate-pulse-soft { animation: pulse-soft 2s cubic-bezier(0.4, 0, 0.6, 1) infinite; }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.1.0/firebase-app.js";
        import { getAuth, onAuthStateChanged, signInWithEmailAndPassword, createUserWithEmailAndPassword, updatePassword, signInWithCustomToken, signInAnonymously } from "https://www.gstatic.com/firebasejs/11.1.0/firebase-auth.js";
        import { getFirestore, doc, setDoc, getDoc, updateDoc, collection, addDoc, onSnapshot, increment } from "https://www.gstatic.com/firebasejs/11.1.0/firebase-firestore.js";
        window.FirebaseSDK = { initializeApp, getAuth, onAuthStateChanged, signInWithEmailAndPassword, createUserWithEmailAndPassword, updatePassword, signInWithCustomToken, signInAnonymously, getFirestore, doc, setDoc, getDoc, updateDoc, collection, addDoc, onSnapshot, increment };
    </script>

    <script type="text/babel">
        const { useState, useEffect, useRef, useMemo } = React;

        const Icon = ({ name, size = 24, className = "" }) => {
            const icons = {
                'smartphone': <path d="M7 2h10a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm5 18h.01" />,
                'history': <path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8m0 0V4m0 4h4m5 4V7m0 5H8" />,
                'settings': <path d="M12.22 2h-.44a2 2 0 0 0-2 2l-.27 1.27a8.73 8.73 0 0 0-1.81.73l-1.21-.46a2 2 0 0 0-2.5 1.1l-.22.44a2 2 0 0 0 1.1 2.5l1.21.46c.07.6.13 1.2.13 1.81s-.06 1.21-.13 1.81l-1.21.46a2 2 0 0 0-1.1 2.5l.22.44a2 2 0 0 0 2.5 1.1l1.21-.46a8.73 8.73 0 0 0 1.81.73l.27 1.27a2 2 0 0 0 2 2h.44a2 2 0 0 0 2-2l.27-1.27a8.73 8.73 0 0 0 1.81-.73l1.21.46a2 2 0 0 0 2.5-1.1l.22-.44a2 2 0 0 0-1.1-2.5l-1.21-.46c-.07-.6-.13-1.2-.13-1.81s.06-1.21.13-1.81l1.21-.46a2 2 0 0 0 1.1-2.5l-.22-.44a2 2 0 0 0-2.5-1.1l-1.21.46a8.73 8.73 0 0 0 1.81-.73l-.27-1.27a2 2 0 0 0-2-2zM12 15a3 3 0 1 1 0-6 3 3 0 0 1 0 6z" />,
                'plus': <path d="M12 5v14M5 12h14" />,
                'trash-2': <React.Fragment><path d="M3 6h18M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2M10 11v6M14 11v6" /></React.Fragment>,
                'chevron-down': <path d="m6 9 6 6 6-6" />,
                'chevron-right': <path d="m9 18 6-6-6-6" />,
                'loader-2': <path d="M21 12a9 9 0 1 1-6.219-8.56" />,
                'eye': <path d="M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7Zm10-3a3 3 0 1 0 0 6 3 3 0 0 0 0-6Z" />,
                'eye-off': <React.Fragment><path d="M9.88 9.88a3 3 0 1 0 4.24 4.24m-7.93-3.05C4.05 12.51 2 12 2 12s3-7 10-7c1.47 0 2.84.34 4.07.94m4.6 4.6c.86 1.02 1.33 1.46 1.33 1.46s-3 7-10 7a8.7 8.7 0 0 1-4.66-1.34M2 2l20 20" /></React.Fragment>,
                'save': <React.Fragment><path d="M19 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11l5 5v11a2 2 0 0 1-2 2z" /><polyline points="17 21 17 13 7 13 7 21" /><polyline points="7 3 7 8 15 8" /></React.Fragment>,
                'user': <React.Fragment><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2" /><circle cx="12" cy="7" r="4" /></React.Fragment>,
                'lock': <React.Fragment><rect x="3" y="11" width="18" height="11" rx="2" ry="2" /><path d="M7 11V7a5 5 0 0 1 10 0v4" /></React.Fragment>,
                'shopping-cart': <React.Fragment><circle cx="8" cy="21" r="1" /><circle cx="19" cy="21" r="1" /><path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12" /></React.Fragment>,
                'check-circle': <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14M22 4L12 14.01l-3-3" />
            };

            return (
                <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`${className} ${name === 'loader-2' ? 'animate-spin' : ''}`}>
                    {icons[name] || null}
                </svg>
            );
        };

        const firebaseConfig = {
            apiKey: "AIzaSyBX99Y1tsrRSpm0fdpm70GFjlw9G4Kt9_E",
            authDomain: "cheap-data-center.firebaseapp.com",
            projectId: "cheap-data-center",
            storageBucket: "cheap-data-center.firebasestorage.app",
            messagingSenderId: "397497828779",
            appId: "1:397497828779:web:7db21bcfb636a0bb24feee",
            measurementId: "G-PB82KSBFP2"
        };

        const appId = "cheap-data-center";
        const PAYSTACK_PUBLIC_KEY = "pk_live_8e753f43f8defed950965395fc04f5dc7ab1035b";

        const DATA_BUNDLES = [
            { id: '1gb', name: '1GB', price: 4.60 }, { id: '2gb', name: '2GB', price: 9.50 },
            { id: '3gb', name: '3GB', price: 13.50 }, { id: '4gb', name: '4GB', price: 18.00 },
            { id: '5gb', name: '5GB', price: 22.20 }, { id: '6gb', name: '6GB', price: 27.00 },
            { id: '8gb', name: '8GB', price: 36.00 }, { id: '10gb', name: '10GB', price: 43.00 },
            { id: '15gb', name: '15GB', price: 63.00 }, { id: '20gb', name: '20GB', price: 83.00 },
            { id: '30gb', name: '30GB', price: 122.00 },
        ];

        function App() {
            const [fb, setFb] = useState(null);
            const [user, setUser] = useState(null);
            const [profile, setProfile] = useState(null);
            const [myOrders, setMyOrders] = useState([]);
            const [activeTab, setActiveTab] = useState('home');
            const [loading, setLoading] = useState(true);
            const [processingOrder, setProcessingOrder] = useState(false);
            const [isLogin, setIsLogin] = useState(true);
            const [showPassword, setShowPassword] = useState(false);
            const [authLoading, setAuthLoading] = useState(false);
            const [authError, setAuthError] = useState("");
            
            const [cart, setCart] = useState([]); 
            const [inputPhone, setInputPhone] = useState("");
            const [selectedBundleId, setSelectedBundleId] = useState("");
            const [isSelectorOpen, setIsSelectorOpen] = useState(false);
            
            const [showCheckoutModal, setShowCheckoutModal] = useState(false);
            const [showDepositModal, setShowDepositModal] = useState(false);
            const [depositAmount, setDepositAmount] = useState("");

            const [newName, setNewName] = useState("");
            const [newPass, setNewPass] = useState("");
            const [updateLoading, setUpdateLoading] = useState(false);
            const [updateMsg, setUpdateMsg] = useState({ text: "", type: "" });

            const cartTotal = useMemo(() => cart.reduce((sum, item) => sum + item.price, 0), [cart]);

            useEffect(() => {
                const checkFirebase = setInterval(() => {
                    if (window.FirebaseSDK) { setFb(window.FirebaseSDK); clearInterval(checkFirebase); }
                }, 100);
                return () => clearInterval(checkFirebase);
            }, []);

            useEffect(() => {
                if (!fb) return;
                const app = fb.initializeApp(firebaseConfig);
                const auth = fb.getAuth(app);
                const unsubscribe = fb.onAuthStateChanged(auth, (u) => {
                    setUser(u);
                    if (!u) { setLoading(false); setProfile(null); }
                });
                return () => unsubscribe();
            }, [fb]);

            useEffect(() => {
                if (!user || !fb) return;
                const db = fb.getFirestore();
                const userRef = fb.doc(db, 'artifacts', appId, 'public', 'data', 'users', user.uid);
                const unsubProfile = fb.onSnapshot(userRef, (docSnap) => {
                    if (docSnap.exists()) {
                        const data = docSnap.data();
                        setProfile(data);
                        setNewName(prev => prev || data.name);
                    } else { setProfile({ isProfileComplete: false }); }
                    setLoading(false);
                }, () => setLoading(false));

                const ordersRef = fb.collection(db, 'artifacts', appId, 'public', 'data', 'orders');
                const unsubOrders = fb.onSnapshot(ordersRef, (snapshot) => {
                    const all = snapshot.docs.map(doc => ({ id: doc.id, ...doc.data() }));
                    setMyOrders(all.filter(o => o.userId === user.uid).sort((a,b) => b.timestamp - a.timestamp));
                });
                return () => { unsubProfile(); unsubOrders(); };
            }, [user, fb]);

            useEffect(() => {
                const script = document.createElement("script");
                script.src = "https://js.paystack.co/v1/inline.js";
                script.async = true;
                document.body.appendChild(script);
            }, []);

            const handleAuth = async (e) => {
                e.preventDefault();
                setAuthLoading(true); setAuthError("");
                const fd = new FormData(e.target);
                const email = fd.get('email').trim();
                const password = fd.get('password');
                const auth = fb.getAuth();
                const db = fb.getFirestore();

                try {
                    if (isLogin) {
                        await fb.signInWithEmailAndPassword(auth, email, password);
                    } else {
                        const userCred = await fb.createUserWithEmailAndPassword(auth, email, password);
                        await fb.setDoc(fb.doc(db, 'artifacts', appId, 'public', 'data', 'users', userCred.user.uid), {
                            name: fd.get('name')?.trim(), 
                            phone: fd.get('phone')?.trim(), 
                            email,
                            walletBalance: 0,
                            createdAt: Date.now(),
                            uid: userCred.user.uid,
                            isProfileComplete: true
                        });
                    }
                } catch (err) { setAuthError(err.message); } 
                finally { setAuthLoading(false); }
            };

            const addToCart = () => {
                if (!inputPhone || !selectedBundleId) return;
                const bundle = DATA_BUNDLES.find(b => b.id === selectedBundleId);
                const newItem = {
                    tempId: Date.now() + Math.random(),
                    phone: inputPhone,
                    bundleName: bundle.name,
                    price: bundle.price
                };
                setCart([...cart, newItem]);
                setInputPhone("");
                setSelectedBundleId("");
            };

            const removeFromCart = (tempId) => {
                setCart(cart.filter(item => item.tempId !== tempId));
            };

            const handlePaystack = (amount, metadata, onSuccess) => {
                if (!window.PaystackPop) return;
                const handler = window.PaystackPop.setup({
                    key: PAYSTACK_PUBLIC_KEY,
                    email: profile?.email || user?.email,
                    amount: Math.round(amount * 100),
                    currency: "GHS",
                    callback: onSuccess,
                    metadata: { custom_fields: metadata }
                });
                handler.openIframe();
            };

            const finalizeOrders = async (method) => {
                if (cart.length === 0) return;
                setProcessingOrder(true);
                const db = fb.getFirestore();
                try {
                    const orderPromises = cart.map(item => {
                        return fb.addDoc(fb.collection(db, 'artifacts', appId, 'public', 'data', 'orders'), {
                            userId: user.uid,
                            recipientNumber: item.phone,
                            bundleName: item.bundleName,
                            price: item.price,
                            status: 'processing', // Initial status
                            paymentMethod: method,
                            timestamp: Date.now()
                        });
                    });
                    await Promise.all(orderPromises);
                    if (method === 'wallet') {
                        await fb.updateDoc(fb.doc(db, 'artifacts', appId, 'public', 'data', 'users', user.uid), { 
                            walletBalance: fb.increment(-cartTotal) 
                        });
                    }
                    setCart([]); 
                    setShowCheckoutModal(false); 
                    setActiveTab('orders');
                } catch (err) { 
                    console.error(err); 
                } finally { 
                    setProcessingOrder(false); 
                }
            };

            const handleUpdateProfile = async (e) => {
                e.preventDefault();
                setUpdateLoading(true);
                setUpdateMsg({ text: "", type: "" });
                const db = fb.getFirestore();
                const auth = fb.getAuth();
                try {
                    if (newName && newName !== profile.name) {
                        await fb.updateDoc(fb.doc(db, 'artifacts', appId, 'public', 'data', 'users', user.uid), { name: newName });
                    }
                    if (newPass.trim().length >= 6) {
                        await fb.updatePassword(auth.currentUser, newPass);
                        setNewPass("");
                    }
                    setUpdateMsg({ text: "Profile updated successfully!", type: "success" });
                } catch (err) {
                    setUpdateMsg({ text: err.message, type: "error" });
                } finally { setUpdateLoading(false); }
            };

            if (loading || !fb) return (
                <div className="min-h-screen flex items-center justify-center bg-[#020617]">
                    <Icon name="loader-2" className="text-indigo-500 w-12 h-12 relative" />
                </div>
            );

            if (!user || !profile?.isProfileComplete) return (
                <div className="min-h-screen flex flex-col items-center justify-center p-6 bg-[#020617] animate-fade-in">
                    <div className="w-full max-w-sm space-y-10">
                        <div className="text-center space-y-2">
                            <h1 className="text-4xl font-black gradient-text uppercase tracking-tighter italic">Cheap Data Center GH</h1>
                            <p className="text-slate-400 font-medium text-sm">Fast. Affordable. Reliable.</p>
                        </div>
                        <div className="glass p-8 rounded-[2.5rem] space-y-6">
                            <div className="flex bg-slate-800/50 p-1.5 rounded-2xl">
                                <button onClick={()=>setIsLogin(true)} className={`flex-1 py-3 rounded-xl text-xs font-bold transition-all ${isLogin ? 'bg-indigo-600 shadow-lg text-white' : 'text-slate-500'}`}>LOGIN</button>
                                <button onClick={()=>setIsLogin(false)} className={`flex-1 py-3 rounded-xl text-xs font-bold transition-all ${!isLogin ? 'bg-indigo-600 shadow-lg text-white' : 'text-slate-500'}`}>REGISTER</button>
                            </div>
                            <form onSubmit={handleAuth} className="space-y-4">
                                {!isLogin && (
                                    <React.Fragment>
                                        <input name="name" required placeholder="Full Name" className="w-full bg-slate-900 border border-white/5 p-4 rounded-2xl outline-none focus:border-indigo-500 focus:bg-slate-800 transition-all text-sm" />
                                        <input name="phone" required placeholder="Phone Number" className="w-full bg-slate-900 border border-white/5 p-4 rounded-2xl outline-none focus:border-indigo-500 focus:bg-slate-800 transition-all text-sm" />
                                    </React.Fragment>
                                )}
                                <input name="email" type="email" required placeholder="Email Address" className="w-full bg-slate-900 border border-white/5 p-4 rounded-2xl outline-none focus:border-indigo-500 focus:bg-slate-800 transition-all text-sm" />
                                <div className="relative">
                                    <input name="password" type={showPassword ? "text" : "password"} required placeholder="Password" className="w-full bg-slate-900 border border-white/5 p-4 rounded-2xl outline-none focus:border-indigo-500 focus:bg-slate-800 transition-all text-sm" />
                                    <button type="button" onClick={() => setShowPassword(!showPassword)} className="absolute right-4 top-4 text-slate-500">
                                        <Icon name={showPassword ? "eye-off" : "eye"} size={20} />
                                    </button>
                                </div>
                                {authError && <p className="text-red-400 text-[10px] font-bold bg-red-400/10 p-4 rounded-2xl text-center leading-relaxed">{authError}</p>}
                                <button disabled={authLoading} className="w-full py-4 bg-indigo-600 hover:bg-indigo-500 rounded-2xl font-black uppercase text-xs transition-all shadow-xl shadow-indigo-600/30 text-white">
                                    {authLoading ? <Icon name="loader-2" size={16} className="mx-auto" /> : (isLogin ? 'Sign In' : 'Create Account')}
                                </button>
                            </form>
                        </div>
                    </div>
                </div>
            );

            return (
                <div className="max-w-md mx-auto min-h-screen pb-40 animate-fade-in">
                    <header className="px-6 pt-10 pb-6 flex justify-between items-end sticky top-0 bg-[#020617]/90 backdrop-blur-xl z-[60]">
                        <div className="space-y-1">
                            <h1 className="text-xl font-black leading-none gradient-text uppercase italic tracking-tighter">Cheap Data Center GH</h1>
                            <p className="text-[10px] font-extrabold text-slate-500 uppercase tracking-widest flex items-center gap-1.5">
                                <span className="w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse"></span> Service Active
                            </p>
                        </div>
                        <div className="text-right">
                            <p className="text-[10px] font-black text-slate-500 uppercase mb-1">Balance</p>
                            <p className="text-xl font-black text-emerald-400 leading-none">₵{profile.walletBalance?.toFixed(2)}</p>
                        </div>
                    </header>

                    <main className="px-6 space-y-8 mt-4">
                        {activeTab === 'home' && (
                            <div className="space-y-8">
                                <div className="relative group">
                                    <div className="absolute -inset-1 bg-gradient-to-r from-indigo-500 to-purple-600 rounded-[2.5rem] blur opacity-25"></div>
                                    <div className="relative bg-gradient-to-br from-indigo-600 to-purple-700 rounded-[2.5rem] p-8 shadow-2xl flex justify-between items-center overflow-hidden">
                                        <div className="absolute -right-4 -bottom-4 opacity-10">
                                            <Icon name="smartphone" size={120} />
                                        </div>
                                        <div className="relative z-10">
                                            <p className="text-indigo-100/70 text-[10px] font-bold uppercase tracking-[0.2em] mb-1">CASH BALANCE</p>
                                            <h2 className="text-4xl font-extrabold tracking-tight">₵ {profile.walletBalance?.toFixed(2)}</h2>
                                        </div>
                                        <button onClick={() => setShowDepositModal(true)} className="relative z-10 bg-white/15 hover:bg-white/25 backdrop-blur-md p-4 rounded-3xl transition-all active:scale-95 shadow-lg">
                                            <Icon name="plus" />
                                        </button>
                                    </div>
                                </div>

                                <div className="glass rounded-[2.5rem] p-8 space-y-6">
                                    <h3 className="text-xs font-black uppercase text-indigo-400 tracking-widest text-center">Buy Data</h3>
                                    <div className="space-y-5">
                                        <div className="space-y-2">
                                            <label className="text-[10px] font-black uppercase text-slate-500 ml-1">Recipient Number</label>
                                            <div className="bg-slate-900/80 rounded-2xl p-4 flex items-center gap-3 border border-white/5 focus-within:border-indigo-500/50 transition-all">
                                                <Icon name="smartphone" size={18} className="text-slate-500" />
                                                <input type="tel" value={inputPhone} onChange={(e) => setInputPhone(e.target.value)} placeholder="05x xxx xxxx" className="bg-transparent w-full font-bold outline-none text-slate-100 placeholder:text-slate-700 text-sm" />
                                            </div>
                                        </div>
                                        <div className="space-y-2 relative">
                                            <label className="text-[10px] font-black uppercase text-slate-500 ml-1">Bundle Size</label>
                                            <button onClick={() => setIsSelectorOpen(!isSelectorOpen)} className="w-full p-4 flex justify-between bg-slate-900/80 rounded-2xl font-bold border border-white/5 hover:border-white/10 transition-all text-sm">
                                                <span className={selectedBundleId ? 'text-white' : 'text-slate-600'}>
                                                    {selectedBundleId ? DATA_BUNDLES.find(b => b.id === selectedBundleId).name : 'Select a bundle'}
                                                </span>
                                                <Icon name="chevron-down" size={18} className="text-slate-500" />
                                            </button>
                                            {isSelectorOpen && (
                                                <div className="absolute top-full left-0 right-0 mt-3 glass rounded-2xl overflow-hidden z-[70] shadow-2xl max-h-56 overflow-y-auto border border-white/10">
                                                    {DATA_BUNDLES.map(b => (
                                                        <button key={b.id} onClick={() => { setSelectedBundleId(b.id); setIsSelectorOpen(false); }} className="w-full p-5 flex justify-between items-center border-b border-white/5 hover:bg-white/10 transition-all">
                                                            <span className="font-bold text-sm">{b.name}</span>
                                                            <span className="text-emerald-400 font-black px-3 py-1 bg-emerald-400/10 rounded-lg text-xs">₵{b.price.toFixed(2)}</span>
                                                        </button>
                                                    ))}
                                                </div>
                                            )}
                                        </div>
                                        <button onClick={addToCart} className="w-full py-5 bg-indigo-600/10 border border-indigo-600/20 hover:bg-indigo-600/20 rounded-2xl font-black uppercase text-xs flex items-center justify-center gap-2 transition-all text-indigo-400">
                                            <Icon name="plus" size={16} /> Add to Cart
                                        </button>
                                    </div>
                                </div>

                                {cart.length > 0 && (
                                    <div className="space-y-4 animate-fade-in">
                                        <div className="flex justify-between items-end px-2">
                                            <h4 className="text-xs font-black uppercase text-slate-500 tracking-widest">Cart Items ({cart.length})</h4>
                                            <p className="font-black text-indigo-400">Total: ₵{cartTotal.toFixed(2)}</p>
                                        </div>
                                        <div className="space-y-3">
                                            {cart.map(item => (
                                                <div key={item.tempId} className="glass p-5 rounded-[2rem] flex justify-between items-center group">
                                                    <div className="flex gap-4 items-center">
                                                        <div className="w-10 h-10 bg-indigo-500/10 rounded-xl flex items-center justify-center text-indigo-400">
                                                            <Icon name="smartphone" size={16} />
                                                        </div>
                                                        <div>
                                                            <p className="font-bold text-sm">{item.phone}</p>
                                                            <p className="text-[10px] text-slate-500 font-bold uppercase">{item.bundleName}</p>
                                                        </div>
                                                    </div>
                                                    <div className="flex items-center gap-4">
                                                        <p className="font-black text-sm text-emerald-400">₵{item.price.toFixed(2)}</p>
                                                        <button onClick={() => removeFromCart(item.tempId)} className="p-2 text-slate-600 hover:text-red-400 transition-colors">
                                                            <Icon name="trash-2" size={18} />
                                                        </button>
                                                    </div>
                                                </div>
                                            ))}
                                            <button onClick={() => setShowCheckoutModal(true)} className="w-full py-5 bg-indigo-600 hover:bg-indigo-500 rounded-2xl font-black uppercase text-xs flex items-center justify-center gap-2 transition-all shadow-xl shadow-indigo-600/20 active:scale-[0.98] text-white">
                                                <Icon name="shopping-cart" size={16} /> PROCEED TO CHECKOUT
                                            </button>
                                        </div>
                                    </div>
                                )}
                            </div>
                        )}

                        {activeTab === 'orders' && (
                            <div className="space-y-6">
                                <h3 className="text-2xl font-black tracking-tight">Order History</h3>
                                {myOrders.length === 0 ? (
                                    <div className="glass p-12 rounded-[2.5rem] text-center space-y-4 border-dashed border-white/10">
                                        <div className="bg-slate-800/50 w-16 h-16 rounded-3xl flex items-center justify-center mx-auto text-slate-500">
                                            <Icon name="history" size={32} />
                                        </div>
                                        <p className="text-slate-500 font-bold text-sm">No orders yet.</p>
                                    </div>
                                ) : (
                                    <div className="space-y-3">
                                        {myOrders.map(o => (
                                            <div key={o.id} className="glass card-glow p-5 rounded-[2rem] flex justify-between items-center">
                                                <div className="flex gap-4 items-center">
                                                    <div className={`w-12 h-12 rounded-2xl flex items-center justify-center transition-colors ${o.status === 'completed' ? 'bg-emerald-500/10 text-emerald-500' : 'bg-orange-500/10 text-orange-500'}`}>
                                                        <Icon name={o.status === 'completed' ? 'check-circle' : 'loader-2'} size={20} className={o.status !== 'completed' ? 'animate-spin' : ''} />
                                                    </div>
                                                    <div>
                                                        <p className="font-black text-sm">{o.recipientNumber}</p>
                                                        <p className="text-[10px] text-slate-500 font-bold uppercase tracking-wider">{o.bundleName} • {new Date(o.timestamp).toLocaleDateString()}</p>
                                                    </div>
                                                </div>
                                                <div className="text-right">
                                                    <p className="font-black text-sm text-emerald-400">₵{o.price.toFixed(2)}</p>
                                                    <div className={`text-[8px] font-black uppercase px-2 py-1 rounded-md mt-1 inline-flex items-center gap-1 ${
                                                        o.status === 'completed' 
                                                        ? 'bg-emerald-500/10 text-emerald-500' 
                                                        : 'bg-orange-500/10 text-orange-500 animate-pulse-soft'
                                                    }`}>
                                                        <span className={`w-1 h-1 rounded-full ${o.status === 'completed' ? 'bg-emerald-500' : 'bg-orange-500'}`}></span>
                                                        {o.status}
                                                    </div>
                                                </div>
                                            </div>
                                        ))}
                                    </div>
                                )}
                            </div>
                        )}

                        {activeTab === 'settings' && (
                            <div className="space-y-8 animate-fade-in">
                                <h3 className="text-2xl font-black tracking-tight">Account Settings</h3>
                                
                                <form onSubmit={handleUpdateProfile} className="glass rounded-[2.5rem] p-8 space-y-8">
                                    <div className="space-y-5">
                                        <div className="space-y-2">
                                            <label className="text-[10px] font-black uppercase text-slate-500 ml-1">Display Name</label>
                                            <div className="bg-slate-900/80 rounded-2xl p-4 flex items-center gap-3 border border-white/5">
                                                <Icon name="user" size={18} className="text-slate-500" />
                                                <input value={newName} onChange={(e) => setNewName(e.target.value)} required className="bg-transparent w-full font-bold outline-none text-slate-100 text-sm" />
                                            </div>
                                        </div>

                                        <div className="space-y-2">
                                            <label className="text-[10px] font-black uppercase text-slate-500 ml-1">New Password (Min 6 chars)</label>
                                            <div className="bg-slate-900/80 rounded-2xl p-4 flex items-center gap-3 border border-white/5">
                                                <Icon name="lock" size={18} className="text-slate-500" />
                                                <input type="password" value={newPass} onChange={(e) => setNewPass(e.target.value)} placeholder="Leave blank to keep current" className="bg-transparent w-full font-bold outline-none text-slate-100 placeholder:text-slate-700 text-sm" />
                                            </div>
                                        </div>
                                    </div>

                                    {updateMsg.text && (
                                        <div className={`p-4 rounded-2xl text-[10px] font-black text-center uppercase tracking-widest ${updateMsg.type === 'success' ? 'bg-emerald-500/10 text-emerald-500' : 'bg-red-500/10 text-red-500'}`}>
                                            {updateMsg.text}
                                        </div>
                                    )}

                                    <button disabled={updateLoading} className="w-full py-5 bg-indigo-600 hover:bg-indigo-500 rounded-2xl font-black uppercase text-xs flex items-center justify-center gap-2 shadow-xl shadow-indigo-600/20 active:scale-95 transition-all text-white">
                                        {updateLoading ? <Icon name="loader-2" size={16} /> : <React.Fragment><Icon name="save" size={16} /> Save Changes</React.Fragment>}
                                    </button>
                                </form>

                                <div className="glass rounded-[2.5rem] p-8 text-center space-y-4">
                                    <p className="text-[10px] font-black text-slate-500 uppercase">Registered Email</p>
                                    <p className="text-sm font-bold">{profile.email}</p>
                                    <button onClick={() => fb.getAuth().signOut()} className="w-full py-4 bg-red-500/10 text-red-500 hover:bg-red-500 hover:text-white rounded-2xl font-black uppercase text-[10px] transition-all">
                                        Logout Account
                                    </button>
                                </div>
                            </div>
                        )}
                    </main>

                    {showCheckoutModal && (
                        <div className="fixed inset-0 bg-[#020617]/95 z-[100] flex items-end sm:items-center justify-center p-4 backdrop-blur-sm">
                            <div className="glass w-full max-w-sm rounded-[3rem] p-10 space-y-8 animate-fade-in max-h-[90vh] overflow-y-auto">
                                <div className="text-center space-y-2">
                                    <p className="text-[10px] font-black text-indigo-400 uppercase tracking-widest">CHECKOUT SUMMARY</p>
                                    <h3 className="font-black text-4xl">₵{cartTotal.toFixed(2)}</h3>
                                    <p className="text-slate-500 text-sm font-bold">{cart.length} orders total</p>
                                </div>
                                <div className="space-y-3">
                                    <div className="max-h-40 overflow-y-auto space-y-2 mb-6 px-2">
                                        {cart.map(i => (
                                            <div key={i.tempId} className="flex justify-between text-[10px] font-bold uppercase text-slate-500">
                                                <span>{i.phone} ({i.bundleName})</span>
                                                <span>₵{i.price.toFixed(2)}</span>
                                            </div>
                                        ))}
                                    </div>
                                    <button disabled={profile.walletBalance < cartTotal} onClick={() => finalizeOrders('wallet')} className="w-full p-5 rounded-2xl border border-indigo-500/20 bg-indigo-500/10 flex justify-between items-center disabled:opacity-30 transition-all hover:bg-indigo-500/20 group">
                                        <div className="flex items-center gap-3">
                                            <Icon name="history" size={20} className="text-indigo-400" />
                                            <div className="text-left">
                                                <span className="font-black text-sm block">Pay from Wallet</span>
                                                <span className="text-[8px] font-bold uppercase text-slate-500 group-disabled:text-red-500/50">
                                                    {profile.walletBalance < cartTotal ? 'Insufficient Balance' : `Remaining: ₵${(profile.walletBalance - cartTotal).toFixed(2)}`}
                                                </span>
                                            </div>
                                        </div>
                                        <Icon name="chevron-right" size={18} />
                                    </button>
                                    <button onClick={() => handlePaystack(cartTotal, cart.map(i=>({p:i.phone, b:i.bundleName})), () => finalizeOrders('paystack'))} className="w-full p-5 rounded-2xl border border-emerald-500/20 bg-emerald-500/10 flex justify-between items-center transition-all hover:bg-emerald-500/20">
                                        <div className="flex items-center gap-3">
                                            <Icon name="plus" size={20} className="text-emerald-400" />
                                            <span className="font-black text-sm">Pay with MoMo</span>
                                        </div>
                                        <Icon name="chevron-right" size={18} />
                                    </button>
                                </div>
                                <button onClick={() => setShowCheckoutModal(false)} className="w-full text-slate-500 font-black uppercase text-[10px] tracking-widest pt-2">Cancel</button>
                            </div>
                        </div>
                    )}

                    {showDepositModal && (
                        <div className="fixed inset-0 bg-[#020617]/95 z-[100] flex items-center justify-center p-4 backdrop-blur-sm">
                            <div className="glass w-full max-w-sm rounded-[3rem] p-10 space-y-8 animate-fade-in">
                                <h3 className="font-black text-2xl text-center tracking-tight">Deposit Funds</h3>
                                <div className="space-y-4">
                                    <div className="bg-slate-900 border border-white/5 rounded-2xl p-6">
                                        <input type="number" value={depositAmount} onChange={(e) => setDepositAmount(e.target.value)} placeholder="0.00" className="w-full bg-transparent p-0 font-black text-4xl text-center outline-none text-emerald-400 placeholder:text-slate-800" />
                                        <p className="text-[10px] text-slate-600 font-bold text-center mt-4 uppercase tracking-widest">Amount to deposit (GHS)</p>
                                    </div>
                                    <button onClick={() => handlePaystack(parseFloat(depositAmount), [], async () => {
                                        const db = fb.getFirestore();
                                        await fb.updateDoc(fb.doc(db, 'artifacts', appId, 'public', 'data', 'users', user.uid), { walletBalance: fb.increment(parseFloat(depositAmount)) });
                                        setShowDepositModal(false); setDepositAmount("");
                                    })} className="w-full py-5 bg-indigo-600 rounded-2xl font-black uppercase shadow-xl shadow-indigo-600/20 active:scale-95 transition-all text-white">Deposit Securely</button>
                                </div>
                                <button onClick={() => setShowDepositModal(false)} className="w-full text-slate-500 font-black uppercase text-[10px] tracking-widest text-center block">Nevermind</button>
                            </div>
                        </div>
                    )}

                    <nav className="fixed bottom-8 left-6 right-6 h-24 glass rounded-[3rem] flex justify-around items-center z-[80] shadow-2xl border-t border-white/10 px-4">
                        <NavBtn active={activeTab === 'home'} onClick={() => setActiveTab('home')} icon="smartphone" label="Shop" count={cart.length} />
                        <NavBtn active={activeTab === 'orders'} onClick={() => setActiveTab('orders')} icon="history" label="Orders" />
                        <NavBtn active={activeTab === 'settings'} onClick={() => setActiveTab('settings')} icon="settings" label="Profile" />
                    </nav>

                    {processingOrder && (
                        <div className="fixed inset-0 bg-[#020617]/95 z-[300] flex items-center justify-center">
                            <div className="text-center space-y-6">
                                <Icon name="loader-2" size={64} className="text-indigo-500 relative" />
                                <p className="font-black uppercase text-xs tracking-[0.4em] text-indigo-400 animate-pulse">Confirming Orders...</p>
                            </div>
                        </div>
                    )}
                </div>
            );
        }

        function NavBtn({ icon, label, active, onClick, count = 0 }) {
            return (
                <button onClick={onClick} className={`flex flex-col items-center gap-2 transition-all duration-300 relative ${active ? 'text-indigo-400 -translate-y-2' : 'text-slate-500 hover:text-slate-300'}`}>
                    <div className={`p-3.5 rounded-2xl transition-all relative ${active ? 'bg-indigo-500/20 shadow-[0_0_20px_rgba(99,102,241,0.2)]' : ''}`}>
                        <Icon name={icon} size={22} />
                        {count > 0 && (
                            <div className="absolute -top-1 -right-1 w-5 h-5 bg-indigo-600 text-white text-[10px] font-black rounded-full flex items-center justify-center border-2 border-[#020617] animate-fade-in">
                                {count}
                            </div>
                        )}
                    </div>
                    <span className="text-[9px] font-black uppercase tracking-tighter">{label}</span>
                    {active && <div className="absolute -bottom-2 w-1.5 h-1.5 bg-indigo-400 rounded-full shadow-lg shadow-indigo-400/50"></div>}
                </button>
            );
        }

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<App />);
    </script>
</body>
</html>
